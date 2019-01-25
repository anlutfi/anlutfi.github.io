---
layout: post
title:  "MarkerFinder"
description: Software that recognizes a collection of fiducial markers from a studio's ceiling laser-captured point-cloud. It the generates a map that aids another software to superimpose special effects based on a camera's position.
date:   2015-11-03 16:48:02 -0200
categories: [portfolio, contract]
permalink: MarkerFinder
image: assets/images/content/mainMarkerFinder.jpg
thumb: assets/images/content/mainMarkerFinder_ogthumb.jpg
---
Coded in <span class="skill">C++</span> with [OpenCV](http://opencv.org/){:target="_blank"}, it was commissioned by [Rede Globo](http://redeglobo.globo.com/){:target="_blank"} from [ICAD/VisionLab]({{ site.baseurl }}/employerICAD){:target="_blank"}. This project's goal was to make the mapping of fiducial markers on a studio's ceiling automatic. This mapping process is a crucial preparation step for the use of [LightCraft](http://www.lightcrafttech.com/){:target="_blank"} Technology. LightCraft uses an extra wide-angle lens equipped to the top of a camera, pointing up to a ceiling covered with fiducial markers. This lens captures the location of these markers and, with a previously known map, calculates the camera's location within the studio. The superimposition of virtual elements over the footage is considerably easier when this location is known. Before <b>MarkerFinder</b>, this mapping was done manually and took about 4 hours. Now, it takes 20 to 40 minutes.<!--more--> Since this was made for a brazilian company, it is documented in Portuguese.  
[Source (C++)](https://github.com/anlutfi/MarkerFinder){:target="_blank"} (requires [OpenCV](http://opencv.org/){:target="_blank"})  
[Visual Studio configuration files](https://github.com/anlutfi/MarkerFinder/tree/master/vstudio%20confs){:target="_blank"}

