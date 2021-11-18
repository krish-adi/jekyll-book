# Blog theme for Jekyll: jekyll-book

## GitBook-inspired theme

This repository contains the files for a **blog theme** for Jekyll. It has been inspired by the styling the functionalities of the GitBook legacy version. 

Live demo of the theme [**here**](https://krishadi.com).

## Usage

1. Clone the repo.

2. Add your posts within the folder `_posts`. Use the folder structure based on the category of the post.

3. Add the mandatory index file `0000-01-01-index.md` inside the category folder within posts.

   `_posts/:category/0000-01-01-index.md`

   With contents:

   ```md

   ---
   title: index
   date: 0000-01-01
   category: code
   layout: category-index
   ---

   ```

4. Setup the config file `_config.yml` with the desired variable values. 

5. Install the dependencies of the theme by running `bundle install` .
   
6. Build the blog and serve it by running `bundle exec jekyll serve` .

## TODO

- Syntax code highlighting fix for dark-mode.
- Add top margin for reference/backlinks that is placed at the bottom. 
