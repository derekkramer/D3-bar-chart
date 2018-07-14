![D3.js]( 	https://s3-us-west-2.amazonaws.com/derek-assets/D3.png)

# D3 Bar Chart Lecture - Part 1

This repository contains several different versions of D3 bar charts, all corresponding to a D3 lecture given to Galvanize WDI, Platte on June 27, 2018. The full-length recorded lecture can be found on YouTube [here](https://youtu.be/mJq_D3UBQTs).  
  
All three versions produce the exact same bar chart using three different D3 methodologies. Each version has two branches, an initial and a final. The initial has the starting codebase at each point in the lecture and the final has the functioning, finished codebase that produces the bar chart. Each version is detailed below:

## Basic

The basic version of the bar chart is the simplest methodology possible. It uses linear scaling functions of D3 to relatively size each `<div>` for every bar in the chart and gives an easy intro into the "chained function" format of D3 as well as its syntax at a high level. The Git command to access each branch can be seen below:

> **Initial:** `git checkout html-initial`  
> **Final:** `git checkout html`

## SVG

This version of the bar chart is produced using D3's native SVG functionality. As was stated before, this version produces the exact same bar chart as the basic version, but here the concepts of _**drawing**_ a graph and SVG syntax in HTML are introduced. Instead of creating a `<div>` for each bar, and being limited to the square shape, this code shows how to move the draw location and provide SVG-syntactical instructions on drawing each bar. This method is imperative to understand when it comes to rendering more complicated and "non-square" data visualizations. The Git command to access each branch can be seen below:

> **Initial:** `git checkout svg-initial`  
> **Final:** `git checkout svg`

## Data

Finally, the data version of this bar chart uses the same SVG drawing technique as before, but introduces D3's native file-reading functionality. While most industry D3 implementations pull from an API, this exercise gives an introduction to dealing with asynchronous data and the rendering flow with changing/awaited data. The Git command to access each branch can be seen below:

> **Initial:** `git checkout data-initial`  
> **Final:** `git checkout data`
