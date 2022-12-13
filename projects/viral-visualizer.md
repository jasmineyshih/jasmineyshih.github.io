---
layout: project
type: project
image: img/viral-viz/viral-square.png
title: "Viral Hashtag Progression Visualizer"
date: 2021
published: true
labels:
  - Web Visualization
  - Social Media Data
summary: "A tool for visualizing how a viral hashtag spreads across Twitter users"
---

I took [CS448B: Data Visualization](https://magrawala.github.io/cs448b-fa21/) at Stanford University in Fall 2021.  For the class final project, I worked with another Stanford master's student, [Ahsan](http://raisulahsan.com/), to build a prototype web visualization tool that displays the progression of social media posts that contain a viral hashtag. In particular, we designed the tool to visualize the posts in a tree-like graph where the edges represent the followed/follower relationships between the authors of the Tweets. This allows us to make inferences about which users might have influenced which of their followers to spread the viral hashtag. The hashtag we decided to examine as an example was #UrbanDictionary.

My contributions to the project were
1. building the node graph view
2. adding interactive features that can be accessed in the left sidebar
3. cleaning the data we obtained from the Twitter API

## Tool Demo
<div class="ratio ratio-4x3 my-4">
  <iframe src="https://www.youtube.com/embed/bwX0uoRmBXs" 
          title="Viral Hashtag Progression Visualizer" 
          allowfullscreen>
  </iframe>
</div>

You can find the tool at [https://jasmineyshih.github.io/CS448B-F21-FinalProject/](https://jasmineyshih.github.io/CS448B-F21-FinalProject/).