[![GitHub version](https://badge.fury.io/gh/Gudbrandr%2FRouteChecker.svg)](https://badge.fury.io/gh/Gudbrandr%2FRouteChecker)
[![GitHub release](https://img.shields.io/github/release/qubyte/rubidium.svg)]()

# RouteChecker

Route Checker is an add-on tool for the [OpenBVE](http://openbve-project.net/) train simulator.

## Purpose

There are a lot of railway routes available for OpenBVE, many of them made for older versions. Many of the available routes also contain errors, either because things have changed since they were made or simply due to human error. Whilst trying to fix some of these errors I discovered that it is very difficult to keep track of elements such as poles, dikes, rails and walls in everything but the shortest of routes, simply due to the numbers of entries that exist for these elements. Each type can have numerous start, stop and modification entries resulting in potentially hundreds or thousands of entries to keep track of. Route Checker can help with this process.

Additionally, many routes were written in the now-deprecated RW format and, whilst this is still supported, the newer CSV format is the preferred option these days and it offers greater facilities for route development. Many of these haven't been updated or converted and it would be a great shame to lose the good work done by the developers of these routes. Route Checker can also convert from RW to CSV format and export a route as CSV so that these routes can be refreshed, enhanced and retained for the future.

More details can be found on the [web site](https://gudbrandr.github.io/RouteChecker/).

## Change Log

### 20170107
* Changed the directory structure to match OpenBVE as I don't see much value in being able to build it separately, given the dependencies.
* Removed unused images.
* Changed the GUI to pull the icon and images from the assets directory
* Removed the .sln from the project again.

### 20170106
* Fixed an omission that caused comments to be repeated when converting to CSV.
* Provided the obvious default file name in the save dlg.
* Suppressed warnings about variables which will always have their default values as this is expected.
* Reinstated Train.Velocity as the docs say that it is used.
* Reinstated Route.DeveloperID so that the author is credited for their work.
* Cleaned up and removed unnecessary code.
* Added the readme to the solution and started a change log.
* Added headers to files that didn't have them.

### 20170102
* Added some documentation.
* Changed the web site's theme.

### 20170101
* Created a Jekyll site.

### 20161230
* Got it working with OpenBVE 1.4.5.0 (master).

### 20161227
* 20161227 Initial commit to GitHub. The code still runs when using OpenBVE 1.4. The sln uses C# 3.0 and targets .Net 3.5.
* Changed .NET target version to 4.5.2.
* Changed to C# 5.
* Added .sln.
