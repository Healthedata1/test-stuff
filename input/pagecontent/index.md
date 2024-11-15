{::options toc_levels="1..6"/}

☝️☝️☝️ \{\:\:options toc_levels="1..6"/\} on first line

### h3 element

Use liquid to create a link list of all the ig pages form the site.data.pages.json  file


{% raw %}
```
{%- for pages_hash in site.data.pages-%}  
{%- assign hash= pages_hash[1] -%}  
{%- assign page = pages_hash[0] -%}  
\ [{{hash.title}}\]: {{page}}  
{% endfor %}  
```
{% endraw %}
try it:

- [Table of Contents]
- [Home]
- [Guidance]
- [Downloads]
- [ImplementationGuide Resource]
- [Change Log]
- [Artifacts Summary]
- [Observation]
- [component]


###  another h3 element

#### h4 element

##### h5 element

###### h6 element

###### Another h6 element with the "no_toc" tag to omit from the toc
{:.no_toc}

☝️☝️☝️  \{\:.no_toc\} right after header

~~~
[Home]: index.html
[Guidance]: guidance.html
[Downloads]: downloads.html
[ImplementationGuide Resource]: ImplementationGuide.html
[Change Log]: changes.html
[Artifacts Summary]: artifacts.html
~~~

{% include link-list.md %}

