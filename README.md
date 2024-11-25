# BSI Landscape

[![CI](https://github.com/naskio/bsi-landscape/actions/workflows/ci.yml/badge.svg)](https://github.com/naskio/bsi-landscape/actions/workflows/ci.yml)

> CNCF > Runtime Technical Advisory Group > Batch System Initiative Working Group

The BSI Landscape is intended as a map of the batch system ecosystem. It is a living document that will be updated as
new batch systems are developed and existing batch systems evolve.

This repository contains the data files and images required to generate the landscape. The software that generates
it can be found at the [cncf/landscape2](https://github.com/cncf/landscape2) repository. Please check it for more
information about how it works.

- [Full landscape](https://bsi-landscape.netlify.app/)
- [Landscape embed view within the tag-runtime BSI page](https://tag-runtime.cncf.io/wgs/bsi/)


Code used to embed the landscape:
```html
<!-- Landscape embed view -->
<iframe 
        src="https://bsi-landscape.netlify.app/embed/embed.html?key=batch-scheduling&headers=true&category-header=false&category-in-subcategory=false&title-uppercase=true&title-alignment=left&title-font-family=sans-serif&title-font-size=14&style=shadowed&bg-color=%23429ff5&fg-color=%23ffffff&item-modal=true&item-name=true&size=lg&items-alignment=left&item-name-font-size=12" 
        style="width:100%;height:100%;min-height:720px;display:block;border:none;">
</iframe>
<!-- Landscape embed item details view -->
<!-- NOTE: the script and the iframe below should only be added once, even when adding multiple embed views to the page -->
<script src="https://bsi-landscape.netlify.app/embed/embed-item.js"></script>
<iframe 
        id="embed-item" 
        src="https://bsi-landscape.netlify.app/embed/embed-item.html" 
        style="width:100%;height:100%;display:block;border:none;position:fixed;top:0;bottom:0;left:0;right:0;z-index:2147483647;display:none;">
</iframe>
```
