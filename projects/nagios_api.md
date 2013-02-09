# Nagios Cache and API

**Summer 2012**

## Project Description

In Emerson IT we use [Nagios](http://www.nagios.org/projects/nagioscore) to monitor all of our systems infrastructure and a lot of our network. I rebuilt the Nagios server from scratch in 2010 (I think), but I always found it cumbersome to get information quickly and easily out of Nagios. I took it upon myself to build my own API to that information. However, an API that tapped directly into Nagios's main datastore proved too taxing for the server, so I revised the first version of the API to use MongoDB as a caching layer. The API now uses a REST API and gives back data in JSON format.

I've recently open-sourced this project so that other sysadmins can get some nice, clean info out of Nagios.

## My Role in the Project

I built it and continue to use it a lot.

## Technology Used

	- PHP
	- Nagios
	- MongoDB
	- JSON

## Link to Source Code and/or the Project Itself

The project: http://bench.emerson.edu/nagios/api.html
The source code: https://github.com/cyle/nagios-cache-api