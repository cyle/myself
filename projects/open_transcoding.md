# The Open Transcoding Platform

**Fall 2012**

## Project Description

[Median](median.md) utilizes a transcoding farm I built to encode video uploads for the web. Originally, the farm was a messy strapped-together combination of software packages, mostly Windows-based, that ran just reliably enough to not be noticeable. However, it created backend headaches for me, and needed to be constantly babysat. For Median 4, I totally rebuilt the transcoding farm using PHP, Debian, and node.js based scripts. For Median 5, I completely ported the database layer from Microsoft SQL to MongoDB, and open sourced it.

The farm works very simply: user uploads a video, it gets put into a repository, nodes grab the file, transcode it to smaller web-friendly versions, and give it back to the file repository. It does this in a loosely centralized fashion that is fault tolerant and horizontally scalable.

## My Role in the Project

I built it.

## Technology Used

- Debian, Ubuntu
- PHP
- node.js
- Bash scripting
- MongoDB

## Link to Source Code and/or the Project Itself

An implementation of it, on Median: http://median.emerson.edu/farming.php
The source code: https://github.com/cyle/transcode-farm