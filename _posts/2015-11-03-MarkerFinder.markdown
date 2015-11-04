---
layout: post
title:  "MarkerFinder"
date:   2015-11-03 16:48:02 -0200
categories: [portfolio, contract]
permalink: MarkerFinder
excerpt_separator: <!--more-->
---
Coded in <span class="skill">C++</span> with [OpenCV](http://opencv.org/){:target="_blank"}, it was commissioned by [Rede Globo](http://redeglobo.globo.com/){:target="_blank"} from [ICAD/VisionLab](http://www.icad.puc-rio.br/){:target="_blank"}. This project's goal was to make the mapping of fiducial markers on a studio's ceiling automatic. This mapping process is a crucial preparation step for the use of [LightCraft](http://www.lightcrafttech.com/){:target="_blank"} Technology. LightCraft uses an extra wide-angle lens equipped to a camera and pointed to the ceiling, which is covered in fiducial markers. This lens captures the location of these markers and, with a previously known map, calculates the camera's location within the studio. The superimposition of virtual elements over the footage is considerably easier when this location is known. Before <b>MarkerFinder</b>, this mapping was done manually and took about 4 hours, now it takes 20 to 40 minutes. Since this was made for a brazilian company, it is documented in Portuguese.  
[Source (C++)](http://www.icad.puc-rio.br/~gameshow/MarkerFinder/sources/){:target="_blank"} (requires [OpenCV](http://opencv.org/){:target="_blank"})  
[Visual Studio configuration files](http://www.icad.puc-rio.br/~gameshow/MarkerFinder/configFilesVStudio/){:target="_blank"}
<!--more-->
