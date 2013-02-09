# Star Wars Web Cluster

**Winter 2011**

## Project Description

I wanted to build a horizontally-scalable web cluster for some of my web applications in Emerson IT. The cluster currently includes two application servers, one master database and file server, a slave/failover database server, and a three-node MongoDB replica set cluster. The cluster currently holds about a dozen sites.

All of the nodes in the cluster are named after Star Wars characters, hence the "Star Wars Web Cluster" name. It sits behind the college's main load balancer, though I have a load balancer should anything happen to that.

## My Role in the Project

Architected, built, and implemented the whole thing.

## Technology Used

	- lighttpd
	- PHP
	- MySQL
	- NFS
	- MongoDB

## Link to Source Code and/or the Project Itself

Nothing to link to, really.