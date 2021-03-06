---
title: "Coursera - Developing Data Products"
author: "Robert Reynolds, PhD"
highlighter: highlight.js
output: pdf_document
job: Coursera Student
knit: slidify::knit2slides
mode: selfcontained
hitheme: tomorrow
subtitle: Final Course Project - Slidify Slides
framework: io2012
widgets: []
---
<style>
em {
  font-style: italic
}
</style>

## Course Project: Data Visualization

Powerful but simple idea: visualize otherwise dense and abstract data, in a way that is intuitive and interactive for the user.  
  <br>
Advantages  
  
1. Easier to comprehend;  
2. Easier to present; and  
3. More interesting for the viewer  

--- .class #id 

## Platform

Data Visualization Platform Considerations:  

1. Development cost (time)  
2. Technology cost (money, hardware resources)  
3. Accessibility to audience  
4. Capabilities and overall look

--- .class #id  

## Shiny  

Shiny offers good balance on the 4 factors:  

1. Easy to learn and develop quickly  
2. Libraries are open source/free  
3. Shiny apps can run in any web browser off a web-based Shiny server  
4. Shiny offers decent customization and integration with html5 for a clean look; has a wide array of html-style form controls to manipulate data.

--- .class #id

## Proposal

1. Adopt Shiny as the "go-to" visualization platform  
2. Create a first project using data from _Reynolds RJ, Day SM. Mortality of U.S. Astronauts, 1980-2009. Aviat Space Environ Med 2010;81:1024-7._
3. Publish to Shiny server  
4. Data preview:  



```
##      cause decade type stat
## 1 External      8    1 1020
## 2 External      9    1  337
## 3 External     10    1  506
## 4      CVD      8    1   36
## 5      CVD      9    1   51
## 6      CVD     10    1   10
```



