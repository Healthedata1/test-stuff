### Guidance

###  another h3 element

#### h4 element

##### h5 element

###### h6 element

###### Another h6 element with the "no_toc" tag to omit from the toc
{:.no_toc}

☝️☝️☝️  \{\:.no_toc\} right after header


### Client Best Practices for Search:

{% include img.html img="test-no-comment.svg" caption="Figure 1: Test SVG No Comment" %}

~~~svg
{% include_relative test-no-comment.svg %}
~~~

{% include img.html img="test-comment.svg" caption="Figure 1: Test SVG with Comment" %}

~~~svg
{%  include_relative test-comment.svg %}
~~~