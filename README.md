# 🍔 Our recipes

## To add a new recipe:

1 - Clone the repo and pull in the latest changes.

2 - Create new markdown file in the `_recipes` folder (see below)

* The front matter in the markdown file should contain the recipe name and any tags for the recipe.
* Tags should be single words, or joined with a dash
* Between the ingredients and method, ensure you insert `<!-- break -->`. This breaks the content into two columns

```
---
name: Recipe name here
tags: individual tags separated by spaces join-with-dashes
---

## What you need

* An ingredient
* Another thing
* Don't forget this

<!-- break -->

## How it's done

Describe how to do the thing.
```

3 - Run `python tag_generator.py` inside the root directory of the project

4 - Commit changes and push to GitHub

## Local development

1. `bundle install`
1. `bundle exec jekyll serve`
