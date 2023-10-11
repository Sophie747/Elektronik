---
tags: 
aliases: 
keywords: []
subject:
  - Physik für TechnikerInnen
  - "322.005"
semester: 1
created: 11. Oktober 2023
professor: Gunther Springholz
---
 

# Kinematik

> [!INFO] Die *Kinematik* beschäftigt sich mit der Beschreibung der Bewegung von Körpern
> Sie beschreibt *wie* sich Körper bewegen, ohne zu fragen *warum*

```dataviewjs
//Some plotly examples require d3 library to work.
//Since it's large and used by few examples,
//I propose a workaround to import d3;
//You need to download dependency from https://d3js.org/d3.v7.min.js
//and place it in your vault.
let path = app.vault.adapter.basePath;//absolute path to your vault
var d3 = require(path+"\\utils\\d3.v7.min.js");

//Replace this block with any example from plotly.com
//NOTE: `Plotly.newPlot` won't work here, use `window.renderPlotly` instead
var data = [
{x:[0,1,2,3,4,5,6,7,8,9],y:[4,4,2,2,3,3,2,2,4,4]},
{x:[0,1,2,3,4,5,6,7,8,9],y:[3,3,1,1,2,2,1,1,3,3]}
];
var layout = {};
var config = {};

window.renderPlotly(this.container, data, layout, config)
```> [!INFO] Definition der Geschwindigkeit
> Durchschnitts Geschwindigkeit: $\langle v \rangle=\frac{x_{2}-x_{1}}{t_{2}-t_{1}} = \frac{\Delta x}{\Delta t}$
> Einheit: $[v] = \frac{m}{s}$






