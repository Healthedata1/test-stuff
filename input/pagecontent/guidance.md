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

{% include provenance-source-table-generator.md %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit.  **[SHALL]**{: #CONF-001} Aliquam tortor erat, semper tristique lorem quis, consequat convallis massa.  In tincidunt massa in sagittis viverra. Mauris vitae ultricies sapien. Nunc volutpat odio eget dolor malesuada, a feugiat felis ultrices. Phasellus tempor ultrices nisl, nec blandit velit ornare quis. Cras est arcu, placerat in turpis nec, pulvinar molestie mauris. Phasellus at neque nunc. Morbi tincidunt varius bibendum.

Donec scelerisque odio a lectus iaculis semper. Morbi scelerisque sem ac nunc euismod, in luctus leo pellentesque. Sed fermentum luctus diam, eget hendrerit odio pharetra in. Nullam feugiat imperdiet libero, et condimentum est. Morbi vel tempus erat. Donec ex nisl, maximus sed augue eu, [**SHOULD**][CONF-002] hendrerit imperdiet sem. Sed quis porttitor tortor. Integer maximus vitae dolor quis ultrices. Aliquam elementum quam nulla. Sed ac consequat nisi, eget dapibus arcu. Aenean sit amet ligula ac arcu blandit porttitor.

Cras dignissim eleifend augue, in aliquam nisl mollis et. Nulla facilisi. Nunc leo velit, gravida quis justo ut, elementum lacinia magna. Nunc orci tellus, tincidunt egestas malesuada in, egestas feugiat sem. Curabitur ultrices lorem mi, vitae sagittis erat cursus vitae. Vivamus vitae metus scelerisque, cursus nulla nec, ultrices elit. Proin finibus, mauris vitae vulputate molestie, sapien turpis blandit nunc, id tincidunt justo dolor a ante.  [**SHALL**][CONF-003]{: #CONF-003} liquam egestas libero sed orci rutrum eleifend.


### Liquid Script to Generate OperationDefinition All Nice N Pretty Like


  Include: operation-table.html

  Usage:
    {%raw%}{% include operation-table.html op=site.data.my_operation %}{%endraw%}

  Or directly:
     {%raw%}{% include operation-table.html op=site.data.my_operation show_metadata=true %}{%endraw%}

  Parameters:
    op              - the OperationDefinition object (required)
    show_metadata   - show the metadata block above the table (default: true)

----

{% include operation-table.html op=site.data.OperationDefinition-docref show_metadata=true %}



### Links to Terminology Packages

##### Value Set Packages

A Value Set Package contains all the expanded value sets required for an implementation guide. In addition to the packages published with US Core, annual value set packages containing value sets expanded with the updated code system versions will be available for the following US Core Versions to assist implementers who require them.

US Core 6.1.0 (published June 2023)

  - [US Core 6.1.0 Value Set Package - 2023-06](#)
  - [US Core 6.1.0 Value Set Package - 2024-05](#)
  - [US Core 6.1.0 Value Set Package - 2025-05](#)
  - [US Core 6.1.0 Value Set Package - 2026-05](#)

US Core 8.0.1 (published June 2025)

  - [US Core 8.0.1 Value Set Package - 2023-06](https://confluence.hl7.org/rest/teamopsfactory/amazon-s3/1.0/buckets/15/content/download?path=HL7%20Project%20Outreach_Medical%20Record%20Reviews%20Interoperability.pptx&targetId=86974058)  <<< **This is a link to the CGP Confluence Site File Storage Container** >>>
  - [US Core 8.0.1 Value Set Package - 2026-05](#)

US Core 9.0.0 (published June 2026)

  - [US Core 9.0.0 Value Set Package - 2026-05](https://raw.githubusercontent.com/HL7/US-Core/refs/heads/master/tree.txt)   <<< **This is a link to the GitHub Repository** >>>

For more information on Value Set Package and how they are created and used, see the [Value Set Package Implementation Guide](https://build.fhir.org/ig/cqframework/vsp-ig/)


