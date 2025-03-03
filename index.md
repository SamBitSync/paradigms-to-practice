---
layout: home
title: Paradigms to Practice
---


> An aspiring cognitive scientist's journey from theoretical understanding to practical programming implementation

## Project Philosophy

 I'm documenting my journey to bridge the gap between theoretical cognitive science concepts and practical programming implementation. This digital garden serves as both documentation and accountability for my learning process.

## Learning Tracks

Core programming skills and theoretical foundations:
[View Learning Tracks](/paradigms-to-practice/learning-tracks/)

## Research Methods

Programming techniques for cognitive science research:
[View Research Methods](/paradigms-to-practice/research-methods/)

## Cognitive Science Projects

Practical implementations of cognitive models and experiments:
[View Cognitive Science Projects](/paradigms-to-practice/cogsci-projects/)

## Development Tools

Python features, IDEs, and essential tools:
[View Development Tools](/paradigms-to-practice/tools/)

## Recent Progress

{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url | relative_url }}) - {{ post.date | date: "%b %d, %Y" }}
{% endfor %}

[View All Journal Entries](/paradigms-to-practice/posts/)

## Current Focus

For the next two weeks, I'm focusing on:
- Establishing the HtDP design recipe methodology
- Completing 5 introductory PyBites challenges
- Setting up the basic structure for a working memory model project
- Documenting connections between program design and cognitive frameworks


## GitHub Repository

[View on GitHub](https://github.com/SamBitSync/paradigms-to-practice)

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

