---
layout: project
type: project
image: img/personal-analogy/analogy-square.png
title: "Personalized Analogy Generator for Large Prices"
date: 2022-03
published: true
labels:
  - Web Visualization
summary: "A prototype tool for generating personalized analogies for large amounts of money based on user's profile"
---

I took CS206: Exploring Computational Journalism at Stanford University in Winter 2022. For this class, we worked in teams on a quarter-long project, and my team's project built upon this paper: [Generating Personalized Spatial Analogies for Distances and Areas](http://idl.cs.washington.edu/papers/spatial-analogies/). We focused on generating personalized analogies to help a Stanford student better understand large amounts of prices that they might encounter during their casual reading online, such as social media posts and online articles.


How I contributed to the project:
1. I was the sole developer of the tool on the team
2. built the interface that prompts user for information, shows navigable embedded tweets, and displays the five best analogies for the amount of money mentioned in the current tweet based on user’s profile
3. built an interactive visualization with D3.js to allow the user to explore all possible analogies and see where the five best analogies selected lie in the graph in relation to other analogy candidates
4. implemented energy function for ranking analogies, based on survey results collected by other teammates

## Project Presentation
<div class="ratio ratio-4x3 my-4">
  <iframe src="https://www.youtube.com/embed/o6727IysaTE" 
          title="Personalized Analogies for Large Prices" 
          allowfullscreen>
  </iframe>
</div>
↪ My part starts at 1:03 and ends at 5:46

You can find the tool at [https://jasmineyshih.github.io/PriceAnalogyExplorer/](https://jasmineyshih.github.io/PriceAnalogyExplorer/).