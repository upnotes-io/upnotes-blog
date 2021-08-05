---
layout: post
title:  "Why taking good notes is critical for a software engineers"
date:   2021-08-05 07:47:56 +0530
categories: notes
author: kamal
---
<!-- Look the author details up from the site config. -->
{% assign author = site.data.authors[page.author] %}

<!-- Output author details if some exist. -->
{% if author %}
<span>
<!-- Personal Info. -->
Written by <a href="{{ author.web }}">{{ author.name }}</a>
</span>
{% endif %}

Software engineers spent a lot of time investigating and figuring out how something should be done and writing final code that becomes part of your repository is just small part of the whole process. Over time I have realised that having good organisation of notes is critical for long term productivity.

There are tons of notes apps in the market with lots of different features but none of them are specifically designed for software engineers.

## Upnotes

Upnotes aims to specifically design a high quality, private notes app for software engineers. Upnotes is going to have tight integration with all the tools used by software engineers. We have started with git as most of us use git for our version control.

1. We automatically create/organised notes by your repositories and auto create a new note based on your current git branch.

2. Documentation should be a natural extension of notes taken by you for your future self, that's why we have a specific area for you to write notes that should act like wiki. Eventually these notes can be shared with everyone once they reach certain maturity. Most of the projects have poor documentation and approaching documentation from the point of view of notes can solve this problem.

## Current features
Upnotes is just starting with few unique benefits like

1. Creating note using your git branch. This allows you to have consistent notes for each of your task.
2. Automatically created directories for organising your notes based on best practices.
3. Private notes that are version control using git
4. Github flavoured and industry standard markdown format with WYSIWYG and markdown support

## Upcoming features
1. First class support for managing quick todos
2. Auto sync of local git repo with cloud providers (Github, google drive etc)
3. Share notes with team using git repo using markdown
4. First class support in markdown to create diagrams

[Download now](https://upnotes.io#download)

We are going to add many more features and improvements... Please join our [discord chat](https://discord.gg/ATZTMeyWsW) for updates

