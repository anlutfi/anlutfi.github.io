---
layout: post
title:  "Region Detection in Images"
description: R script that divides an images within regions using Random Walks
date:   2015-11-03 16:47:59 -0200
categories: [portfolio, document]
permalink: RegionDetection
image: assets/images/content/mainRegionDetection.jpg
thumb: assets/images/content/mainRegionDetection_ogthumb.jpg

---
Coded in <span class="skill">R</span>, it uses random walks in images to segment them into regions. We implemented the [original Algorithm by Leo Grady](http://vision.cse.psu.edu/people/chenpingY/paper/grady2006random.pdf){:target="_blank"}, as well as an altered version that sets the maximum number of steps in a walk, limiting the computing time. It's a trade-off between accuracy and performance. <br>This was a requirement for a Stochastic Simulation course and was made by me and Ericsson Leal.  
[Source (R)](https://github.com/anlutfi/RegionDetection){:target="_blank"}<br>
[Presentation PPT(Portuguese)](https://www.dropbox.com/s/newlfm2pj332vk2/Segmenta%C3%A7%C3%A3o%20de%20imagem%20com%20passeios%20aleat%C3%B3rios.pptx?dl=0){:target="_blank"}
