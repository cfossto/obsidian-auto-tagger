# obsidian-auto-tagger
This is an auto-tagger plugin written in Python for Obsidian that I use to properly mark important things in my notes.

This is strictly a prototype. Please do not judge my Python skills on this project alone.
I am going to do aweful stuff here..

## Overview
I use Obsidian for many things. I use it for work for reporting/diary. For private stuff I write articles, essays
and sketches and ideas. For all of this I find that the most interesting way to keep track of events,
interesting people, stages and places is to simply tag them. These tags then form a network of ideas
that you can trace. If I want to gather information, I simply go to my tags and click on them to get
very fast access to that information.

## The problem
I find that tagging all the things I find important is quite a hassle to do.
It becomes a chore and an afterthought (since you are writing and tagging afterwards). I'd rather have an app doing that. This one.

## Solution
The solution? AI/NLP, of course. But not the scary kind of AI.

This app goes through your vault (specified by VAULT_LOCATION), goes through your notes
and tags your notes automatically. For my part I find that people, places, products,
nouns in general, technical terms and events interesting. These are tagged by default.

## The app
This app is under construction. It uses spaCY for NLP analysis (primarily Swedish for now).
I am primarily targeting POS 
