---
layout: post
title:  "Connect Roads"
summary: "A small puzzle game to build a road to the finish line"
author: sanathkukkillaya
date: '2022-12-18 2:35:23 +0530'
category: ['personal_projects']
tags: jekyll
thumbnail: /assets/img/posts/connect-roads-thumbnail.png
keywords: personal, project, personal projects, connect roads, drag and drop, isometric grid, audio, settings
usemathjax: false
permalink: /portfolio/connect-roads/
---
<img
      class="card-img-top"
      src="/assets/img/posts/connect-roads-gameplay.jpg"
      alt="connect-roads-gameplay"
/>

This is my first game made using Unity game engine. I created this game to showcase my Unity understanding to my manager at the time, who gave the basic idea for this project. This is a project that is close to my heart since I worked on it fully from ground zero.

The objective of the game is to connect the pieces of the road to create a pathway between the start point of the car and the finish line. There are a total of 9 levels in the game. A level is completed once a path is available from start to end. Player can collect upto 3 stars per level. The pieces can be moved by dragging them. Pieces with orange colour cannot be moved.

#### Highlights:
- Completely developed the game from scratch without any help from my colleagues.
- Created a 3x3 grid system and developed a drag and drop system to move the pieces around one grid at a time.
- Used navmesh to dynamically determine a path from the start line to finish line every time a block is moved.
- Created smoke particle animations for the car movement.
- Added a star collection system to increase the score for each level.
- Designed 9 levels of the game with increasing difficulty.
- Added music and car sounds to the game, and provided the ability to toggle it in game.
- Added a store system for an Android version with basic IAP.
- Created a render texture system to display 3d version of the car models on the shop screen. The shop screen is not available in the web build of the game.

A playable web version of the game has been uploaded on Unity Play.  
[Unity Play](https://play.unity.com/mg/other/connect-roads)  
[Github](https://github.com/sanathkukkillaya/connect-roads)  