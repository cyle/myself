# FUCK READER

**July 2013 - Present**

## Project Description

Oh snap, Google Reader died. I really, really liked Google Reader, and I really, really don't like any of the alternatives that have popped up since it announced its own death. So I took it upon myself, as many other hipster hackers did, to build my own Google Reader alternative. I came up with FUCK READER, and it works exactly how I want it to. I have a few of my friends also using it, and they like it a lot. I still need to perfect some things, like RSS fetching, but it's a work in progress.

Scaling it has been difficult. I binged on MySQL indexing optimization for a week before I got it just right, and now it purrs a lot friendlier than it did in the beginning. Right now the feed ingest uses Ruby, but I'm thinking of rebuilding that piece in Go. I tried using Redis to speed it up, but that didn't help at all.

## My Role in the Project

I built it, of course. And I use it every damn day.

## Technology Used

- PHP, HTML5, jQuery for the front-end
- MySQL, heavily optimized, for the database-end
- Ruby, for the feed ingest
- the [Feedzirra](https://github.com/pauldix/feedzirra) library to help with RSS parsing

## Link to Source Code and/or the Project Itself

No source code available yet, but soon. The site is [here](https://fuckreader.com/). If you want an invite, hit me up on [twitter](http://twitter.com/cylegage) or something.