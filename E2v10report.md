---
title: "Examination of HPV16 E2 in immoralized NOKs and TCGA HNSC"
author: "Tara Nulton"
date: "May 7, 2018"
output:
  html_document:
    df_print: paged
    keep_md:  true
---



# Introduction

Methods to analyze the data for TCGA, E2 and full genome RNA-seq data was generated and analysed from methods previously published (Evans, 2017).  

To generate lists of significantly differentially expressed genes, the following strategy was employed:  

For E2 and full genome clones, genes were considered significant if the internal adjusted p-value from DESeq was less than 0.05 and must also pass a 1.5 fold change.

For TCGA data, a BH correction was applied using an FDR 0.001 and genes were considered significant if the p-value < adjusted p-value and must also pass a 1.5 fold change. 

# Intersections 

<!--html_preserve--><div id="htmlwidget-0aa193cecc227ff8f646" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-0aa193cecc227ff8f646">{"x":{"filter":"none","data":[["1","2","3","4","5"],["HPV16 E2 NOK2","HPV16 full genome NOKs","TCGA HPV16+ HNSC/non HPV HNSC","TCGA E2 HNSC/non HPV HNSC","TCGA no E2 HNSC/non HPV HNSC"],[167,775,2361,2427,609],[null,52,29,30,12],[395,817,2713,2625,1521],[null,397,136,131,64],[null,1.85975e-033,0.015338292,0.012592674,0.004231151],[null,1.1479e-206,8.64371e-028,1.95303e-026,2.31074e-009]],"container":"<table class=\"display\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>X<\/th>\n      <th>Up<\/th>\n      <th>Intersection<\/th>\n      <th>Down<\/th>\n      <th>Intersection.1<\/th>\n      <th>p.value.up<\/th>\n      <th>p.value.down<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[2,3,4,5,6,7]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->

# Venns



![](Image2.tif)

![](Presentation1.tif)


