# SIGIL Spatial/Graph Database

**August 2013**

## Project Description

I wanted to make a database that stores spatial information (Euclidean space) and graph information. So you have nodes that have positions in space, and connections to other nodes. That's pretty much it. I built it in Go with a REST interface, with features like "find shortest path from node X to node Y" or "get adjacent nodes", etc. I was originally going to use [neo4j](http://www.neo4j.org/) but found it too... bloated. I also used this project as an opportunity to learn [Go](http://golang.org/) and a bunch of fun graph algorithms.

## My Role in the Project

I built the damn thing.

## Technology Used

- Go
- gorest Go module
- A* shortest path algorithm

## Link to Source Code and/or the Project Itself

[Check it out!](https://github.com/cyle/sigil)