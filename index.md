---
title       : Network biology overview
subtitle    : 
author      : Keith Hughitt
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]
mode        : selfcontained # {standalone, draft}
github:
    user: khughitt
    repo: slidify-network-biology
---.segue .dark

<!-- Custom Styles -->
<style type='text/css'>
    slides > slide {
        height: 800px;
        margin-top: -400px;
    }
    img {
        max-height: 560px;
        max-width: 964px;
    }
    slide a {border-bottom: none;}
    .references li { font-size: 18px; }
</style>

<!-- Custom JavaScript -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>

<!-- Slides start here -->
## Overview

---

## TODO

1. Types of networks
2. Data used
3. Approaches (PGM, Bayesian nets, correlation, etc.)
4. Research questions that networks can be used to address
5. Network concepts (more from Kwame in a couple weeks...)

---

## The Big Picture

### Why networks?

- For most of the history of biology, a reductionist approach has been used to
  understand different parts of an ecosystem, an organism, a cell, etc.
- This has gotten us pretty far, but you can only understand so much by looking
  at things piecemeal...
- It is only by looking at how all of the parts work together (as a "system")
  that we can truly understand how something works.

---

## An analogy

<span class='caption'>source: http://onlyhdwallpapers.com/wallpaper/cars_golf_volkswagen_parts_desktop_1440x900_hd-wallpaper-44957.jpg</span>
![car parts](assets/img/cars_golf_volkswagen_parts_desktop_1440x900_hd-wallpaper-44957.jpg)

---

## Types of Biological Networks

1. Cell signalling
2. Metabolic interactions
3. Protein-protein interaction
4. Co-expression
5. Transcription-factor binding
6. Protein-phosphorylation
7. Genetic interaction
8. Gene regulatory

**Basic goal**: understand cellular phenomena at a systems scale.

---

## Types of data used to construct biological networks

1. Flow cytometry
2. Expression data (Microarray, RNA-Seq)
3. TF binding (ChIP-chip, ChIP-Seq, etc)

---

## Transcription-factor binding networks

- Chromatin immunoprecipitation (ChIP)
    - Provides information on *in vivo* protein-DNA binding 
      associations.
    - Antibodies targeting specific proteins are used to pull-down proteins in
      a sample and then associated DNA fragments measured.
    - E.g. ChIP-chip and ChIP-Seq


---

## References





- Peter J. Park,   (2009) Chip–Seq: Advantages And Challenges of A Maturing Technology.  <em>Nature Reviews Genetics</em>  <strong>10</strong>  669-680  <a href="http://dx.doi.org/10.1038/nrg2641">10.1038/nrg2641</a>
- X. Zhu, M. Gerstein, M. Snyder,   (2007) Getting Connected: Analysis And Principles of Biological Networks.  <em>Genes & Development</em>  <strong>21</strong>  1010-1024  <a href="http://dx.doi.org/10.1101/gad.1528707">10.1101/gad.1528707</a>





