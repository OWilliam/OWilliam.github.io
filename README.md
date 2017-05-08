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

### Markdown summary

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/OWilliam/OWilliam.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
