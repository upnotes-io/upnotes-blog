---
layout: post
title:  "Why taking good notes is critical for a software developers"
date:   2022-07-05 07:47:56 +0530
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

Software engineers spent a lot of time investigating and figuring out how something should be done and writing final code that becomes part of your repository is just small part of the whole process.
Lots of the context like investigating, trying different solutions, going through docs etc is not captured in out final code change.
Over time, I have realised that taking good notes for each task having good organisation of notes is critical for long term productivity. 
This also helps in improving productivity with context switching.

There are tons of notes apps in the market with lots of different features but none of them are specifically designed for software engineers. 
You can use any of the app which suites your needs, but I feel that there are lots of small things that can be build to have a great note-taking experience.

### My note-taking system:
I divide my notes into following sections:
- rough notes: Any quick pasting of json, links that I am investigating. Anything I might need today or in near term etc.
For each repository I am working on:
- tasks: One note for each task with just brain dump\. This also help me in context switching\. I usually put links\, curl for test apis\, response objects\.
- git tasks: One note for each branch that I am working on\.
- wiki: anything long term that I might need\. For example quick docker commands\, startup scripts\. Links to cheatsheets\. Frequently used database queries etc\.
- todos: A simple todo list to remember things.
- interviews: One note for each candidate.
- meetings: One note for each meeting.
- blogs: Initial blog ideas. Lots of these are incomplete, but I still write the concepts whenever I get the motivation.

I keep my notes in a git repo and sync it in a private github repository.
This allows me to keep history of all my notes, and I never have to worry about loosing my notes.
I delete my old notes to keep my current notes state clean because I always know I can go back and get the deleted notes if I need them.

Every developer knows that context switching is the hardest thing, and you should try to minimize it, but sometimes it is unavoidable, and you should also learn to deal with it.
For example, you are building a feature and a production issue came. You now have to quickly switch your context to debug the production issue. If you have a habit of taking good notes you can quickly come back to previous mental state after fixing the production issue.
A good note-taking system helps in being more productive. Just keep dumping your mind state in a note so that you can come back to the same state quickly once you get back to any task.

## Upnotes
To make developers more productive we are building a notes app by taking inspiration from above system.
This is still in the early stage, and it provides you capability to do all the above things.
One special feature that I like is the ability to create note automatically when you create a new branch in git.

1. Rough notes support with timestamp based naming
2. Auto Git sync to Github/Gitlab etc.
3. todo list support
4. Simple and familiar [Manaco](https://microsoft.github.io/monaco-editor/) editor which is used on VS code also.
5. Out of the box template for developers for each git repo.

I am also looking to talk to other developers out there. Please join our [discord channel](https://discord.gg/ATZTMeyWsW) and say hi if you want to discuss this with me.
You can also ping me on [Twitter](https://twitter.com/kamalkishor1991)
