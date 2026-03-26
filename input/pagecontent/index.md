{::options toc_levels="1..6"/}

☝️☝️☝️ \{\:\:options toc_levels="1..6"/\} on first line

### h3 element

<span style="font-size:1.5em">&#9940;</span>

<span style="font-size:1.5em">&mdash;</span>

<span style="font-size:1.5em; font-weight: bold">&mdash;</span>

<strong><span style="font-size:1.5em">&mdash;</span></strong>


<span class="glyphicon glyphicon-ok-circle"></span>


<span class="glyphicon glyphicon-ok-circle" style="color: #ff0000;"></span>


{% raw %} {{page.path}}  {% endraw %}  = {{page.path}}

{% raw %} {{page.url}}  {% endraw %}  = {{page.url}}

{% raw %} {{page.title}}  {% endraw %}  = {{page.title}}

{% raw %} {{page.dir}}  {% endraw %}  = {{page.dir}}

{% raw %} {{page.name}}  {% endraw %}  = {{page.name}}



###  another h3 element

#### h4 element

##### h5 element

###### h6 element

###### Another h6 element with the "no_toc" tag to omit from the toc
{:.no_toc}

☝️☝️☝️  \{\:.no_toc\} right after header

{% raw %}
👇👇👇 included link list file
~~~
{ % include r4-link-list.md % } <-- static list of a R4 resources
{ % include page-link-list.md % } <--Uses liquid script to create a link list of all the ig pages from site.data.pages.json
~~~
{% endraw %}

hidden content looks like 👇👇👇
~~~
{% include page-link-list.md %}
~~~


Try it:

- `[Table of Contents]` --> [Table of Contents]
- `[Home]` --> [Home]
- `[Guidance]` --> [Guidance]
- `[Downloads]` --> [Downloads]
- `[ImplementationGuide Resource]` --> [ImplementationGuide Resource]
- `[Change Log]` --> [Change Log]
- `[Artifacts Summary]` --> [Artifacts Summary]
- `[Observation]` --> [Observation]
- `[component]` --> [component]


### Cross Version Comparisons

The table below summarizes the different profiles and resource types between Argonaut Data Query and major releases of US Core :

{% include dstu2-r4-table2.md %}



{% include link-list.md %}

