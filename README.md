# How to make a blog post

- Go to [/src/content/posts](/src/content/posts)
- Click on "Add file"
- Paste the following preamble and adapt the relevant parts:
```
---
title: "TITLE"
date: 2025-04-02T20:00:00Z 
image: "/images/logo.png" 
categories: ["current events"] 
authors: ["Julien Riou"] 
tags: ["us"] 
draft: false 
---
TEXT HERE
```
- Write your `title`
- Put the current `date` (it will determine the order of the blogposts)
- Put the name of your `image` if you have one (or leave it to use the standard SNIDDY logo) 
- Add one or several `categories` (create new ones or check for existing [categories](https://sniddy.ch/categories/))
- Put one or several `authors` (this should link to your SNIDDY profile)
- Add one or several `tags` (create new ones or check for existing [tags](https://sniddy.ch/tags/))
- Set `draft` as true if you don't want the post to be published yet
- Optional: add your image in png or jpg at the following path: [public/images](public/images) (with the same name as in the preamble)
- Press commit. If you commit to the main branch the website will update automatically in a few minutes. If you create a new branch you can then ask for a pull request and have someone validate it.
