---
layout: post
title: "Illinois License Data Visualizations"
date: 2025-04-05
---

## First Plot: Licenses by Type and Status

This plot shows how license counts vary across different license types and their current statuses...

<div id="vis1"></div>

## Second Plot: Interactive County Breakdown

This chart explores how licenses are spread across counties, filtered by type...

<div id="vis2"></div>

## Data + Notebook
[The Data](https://github.com/UIUC-iSchool-DataViz/is445_data/raw/main/licenses_fall2022.csv)  
[The Analysis](https://github.com/dgeni2/dgeni2.github.io/python_notebooks/licenses-visualization.ipynb)

<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/vega@5"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/vega-lite@5"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>
<script>
  vegaEmbed('#vis1', '/assets/chart1.vl.json');
  vegaEmbed('#vis2', '/assets/chart2.vl.json');
</script>