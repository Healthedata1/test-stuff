<!-- DocumentReference-insurance-card-intro.md -->

{% assign my_page = page.name | remove: '.html' %}
{% assign my_title = site.data.[my_page].meta.extension[0].valueString %}
{% assign my_contentType = site.data.[my_page].content[0].attachment.contentType %}
{% assign my_data = site.data.[my_page].content[0].attachment.data %}

{% if my_contentType == "application/pdf" %}
  <iframe src="data:{{my_contentType}};base64,{{my_data}}"
          width="100%"
          height="300px">
  </iframe>

{% elsif my_contentType == "text/plain" %}
  <pre id="text-content" style="border:1px solid #ccc; padding:1em; overflow:auto; height:300px;"></pre>
  <script>
    const base64 = "{{ my_data }}";
    const decoded = atob(base64);
    document.getElementById("text-content").textContent = decoded;
  </script>

{% else %}
  <img src="data:{{my_contentType}};base64,{{my_data}}" alt="{{my_title}}" />
{% endif %}