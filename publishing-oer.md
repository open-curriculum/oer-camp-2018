# Publishing OER with Git Pages

## Pedagogy

### Learning objectives

### Topics

## Creating a Table of Contents (TOC)

## Adding a citation

### Visible attribution

“[DMD 100: Digital Multimedia Design Foundations](https://www.gitbook.com/book/dmd-program/dmd-100-sp18/details)” by Michael Collins is licensed under [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/).

`“<a href="https://github.com/dmd-program/dmd-100-sp18">DMD 100: Digital Multimedia Design Foundations</a>” by Michael Collins is licensed under <a href="https://creativecommons.org/licenses/by/4.0/">CC-BY-4.0</a>.`

### OER Schema metadata attribution:

Add [OER Schema](http://oerschema.org) and CC License to HTML source:

```
<!-- Add OERSchema and CC schema vocabulary to object -->
<div resource="#oer-source-id" prefix="oer: http://oerschema.org/ cc:http://creativecommons.org/ns dc:http://purl.org/dc/terms/">



        <!-- Add OER resource text and media here. -->


        <!-- Link the license and attribution to the page -->
        <link about="#oer-source-id" property="cc:license" content="https://creativecommons.org/licenses/by/4.0/">
        <meta about="#oer-source-id" property="cc:attributionUrl" content="https://www.gitbook.com/book/dmd-program/dmd-100-sp18">
        <meta about="#oer-source-id" property="cc:attributionName" typeof="oer:Resource" content="Michael Collins">

</div>
```