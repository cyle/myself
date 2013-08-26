# Emerson Server Stats on Bench

**Fall 2012**

## Project Description

In an effort to centralize monitoring of Emerson's large systems infrastructure, I built a [Statsd](https://github.com/etsy/statsd) server, and then a simple front-end page that displays current server loads. This page includes information from our [Nagios](http://www.nagios.org/projects/nagioscore) server, which performs more in-depth monitoring. This page gives us in IT a robust heads-up display of problems in real time.

## My Role in the Project

I built the server, installed Statsd, customized load reporting scripts, implemented it across the Emerson infrastructure, and built some of these front-end pages to act as HUDs.

## Technology Used

- [Statsd](https://github.com/etsy/statsd)
- [Nagios](http://www.nagios.org/projects/nagioscore)
- Python
- good old HTML

## Link to the Project Itself

[Check it out.](http://bench.emerson.edu/stats/) There's also an iPad/Retina version [here](http://bench.emerson.edu/stats/ipad.php).