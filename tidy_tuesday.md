---
layout: page
title: Tidy Tuesday
---

Welcome to my Tidy Tuesday page! Whenever I have the motivation, I dive into different datasets, choosing whichever one catches my interest at the time.
While I sometimes create multiple visualizations, here you'll only find one per project. Feel free to click into each to explore my code and any additional visualizations (if I have them).

<style>
  .project-gallery {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    align-items: flex-start;
  }

  .project-item {
    position: relative;
    height: 200px;
    overflow: hidden;
    cursor: pointer;
    border-radius: 4px;
  }

  .project-item img {
    height: 100%;
    width: auto;
    display: block;
    border-radius: 4px;
    transition: transform 0.3s ease;
  }

  .project-item:hover img {
    transform: scale(1.05);
  }

  .project-overlay {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    opacity: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 16px;
    font-weight: bold;
    text-align: center;
    padding: 0 5px;
    transition: opacity 0.3s ease;
  }

  .project-item:hover .project-overlay {
    opacity: 1;
  }
</style>

<div class="project-gallery">

  <!-- X-Men TidyTuesday Project -->
  <a class="project-item" href="https://github.com/helenpeng04/tidytuesday/blob/6f39a141623f1e14f90e9f5a90c87ee55cbbda7c/MutantMoneyball.Rmd" target="_blank">
    <img src="https://github.com/helenpeng04/tidytuesday/blob/6f39a141623f1e14f90e9f5a90c87ee55cbbda7c/xmen_appearances_plot.png?raw=true" alt="Mutant Moneyball">
    <div class="project-overlay">Mutant Moneyball (X-Men Appearances)</div>
  </a>

</div>
