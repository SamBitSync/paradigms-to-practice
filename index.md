---
layout: home
title: Paradigms to Practice
---

# A Cognitive Scientist's Digital Garden

Welcome to my learning journey, where I'm bridging the gap between paradigmic cognition and practical programming skills. This digital garden documents my progress, challenges, and insights along the way.

## Learning Areas
- [HtDP (How to Design Programs)](/paradigms-to-practice/htdp) - Structural program design
- [Python Skills](/paradigms-to-practice/python) - Practical implementation
- [Downey Books](/paradigms-to-practice/downey-books) - Computational thinking
- [Cognitive Science Projects](/paradigms-to-practice/cogsci) - Applied programming

## Recent Updates
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## Current Focus
- HtDP Chapter 1
- PyBites Newbie Challenges
- Setting up testing environment

## Progress Tracker
<div class="progress-container">
  <div class="progress-item">
    <h3>HtDP</h3>
    <div class="progress-bar">
      <div class="progress" style="width: 5%"></div>
    </div>
  </div>
  <div class="progress-item">
    <h3>Python</h3>
    <div class="progress-bar">
      <div class="progress" style="width: 10%"></div>
    </div>
  </div>
  <div class="progress-item">
    <h3>Downey Books</h3>
    <div class="progress-bar">
      <div class="progress" style="width: 2%"></div>
    </div>
  </div>
</div>

<style>
.progress-container {
  margin: 20px 0;
}
.progress-item {
  margin-bottom: 15px;
}
.progress-bar {
  background-color: #eee;
  border-radius: 4px;
  height: 20px;
  width: 100%;
}
.progress {
  background-color: #4caf50;
  height: 20px;
  border-radius: 4px;
}
</style>