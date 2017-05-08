---
title: Top Page
---

## Notes on Natural Language Processing, Machine Learning and Neural Nets

On these pages, I will note my progress in understanding natural language processing.

A few months ago, I implemented a NLP system in C++ based on Winograd's seminal SHRDLU paper. As he and subsequent researchers found, building a machine to understand language using hand-coded logical rules
is hard, error prone and ultimately leads to brittle systems. More recent NLP work has focussed on recurrent and deep neural network architectures, leading to significant improvements in machine translation and language
understanding. However, to me it seems that there is something fundamentally missing from the latter approach. It relies on having much data and slowly training the network to discover the minima of its objective function
whereas much human understanding **does** rely on one-shot, 'aha'-moment learning. We form logical rules, best-guess heuristics, exceptions and categorisations without millions of examples. Maybe the deep-learning
approach works at the lowest level of feature abstraction while there are more hard-edged, less fuzzy processes occuring higher up? Maybe neural nets will learn how to perform the hard-edged logic if left for long enough?
Maybe more investigation is required... and that is the subject of this blog.

As well as waffly philosophical stuff like the above, I'll provide detailed notes on how I've got systems up and running. The primary aim is to provide useful resources to the engineer, although the resources may be
covered in a rather meandering manner as I explore these new frontiers in knowledge engineering.

## Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
