---
layout: post
title:  Computer Vision Engineer @ EnVsion
description: Employment at a Deep Video Intelligence company. I wrote software to extract information from video with Computer Vision and Deep Learning.
date:   2020-06-01 16:48:09 -0200
categories: [previous, employment]
permalink: employerENVSION
excerpt_separator: <!--more-->
---

I was a Computer Vision Engineer at [EnVsion](https://www.envsion.io/){:target="_blank"} from<b> June 2020</b> to <b>July 2021</b>

[EnVsion](https://www.envsion.io/){:target="_blank"} develops a video productivity platform to make teams faster and more efficient. Specifically, on top of usual editing functionalities, they use AI to understand video contents and allow indexing and search operations much more powerful than what's currently available.

As a member of the founding team of this early stage company, apart from the following technical aspects of my role, I also got to witness and participate on company structuring and strategic activities.

I wrote code to extract information from video with <span class="skill">Computer Vision</span>, <span class="skill">Deep Learning</span>, and <span class="skill">Natural Language Processing(NLP)</span>. Code is usually in <span class="skill">Python</span>. Computer Vision applications, that range from object/people detection to OCR, usually use <span class="skill">OpenCV</span>, <span class="skill">Tesseract</span>, <span class="skill">TensorFlow</span>, and <span class="skill">PyTorch</span>. For NLP tasks, it's common to use <span class="skill">Spacy</span>. Exeperiments frequently relied on <span class="skill">Jupyter Notebooks</span>. Models, when possible, take advantage of GPU, using <span class="skill">CUDA</span> and <span class="skill">cuDNN</span>.

On top of these ML activities, I also participated in the deployment of AI services using <span class="skill">AWS</span>'s tools that include:
* <span class="skill">ECR</span> and <span class="skill">ECS</span>, for running <span class="skill">Docker</span> containers
* <span class="skill">SQS</span> and <span class="skill">SNS</span>, for communicating between <span class="skill">AWS</span>'s components and [EnVsion](https://www.envsion.io/){:target="_blank"}'s API
* <span class="skill">Lambda</span> functions for short tasks, such as video transcoding, for example
* <span class="skill">Transcribe</span> for extracting transcript from video
* <span class="skill">S3</span>, <span class="skill">CloudWatch</span>, and <span class="skill">IAM</span> roles, as you can't get much done in <span class="skill">AWS</span> without them

Some examples of what I've done include:
* Writing classes that make object detection easier, abstracting the underlying models, such as <span class="skill">YOLO</span>, <span class="skill">Mask RCNN</span>, and <span class="skill">SSD</span>, for example
* Using and tweaking the implementation of <span class="skill">Deep SORT</span> for object tracking
* Creating a simple and modular pipeline structure for plugging and unplugging deep learning functionalities
* Creating a template class that allows an AI tool to listen to an <span class="skill">AWS</span> <span class="skill">SQS</span> queue for videos to be processed and its results to be posted where they need. Almost all of [EnVsion](https://www.envsion.io/){:target="_blank"}'s AI services extended this class
* Using <span class="skill">Aeneas</span> audio alignment library to realign manually edited portions of an auto-generated transcript to the video's audio track
* Segmenting videos in separate shots, using <span class="skill">TransNetv2</span>
* Celebrity detection using <span class="skill">AWS</span>'s <span class="skill">Rekognition</span>
* Extracting text from presentation/class videos with <span class="skill">Tesseract</span>
* Multiple Deep Learning functionalities in road-related videos. Such as a vehicle counter and a make/model identifier that crosses information with license-plate data to detect fraud. (EnVsion started focusing on traffic videos)

The team members all worked remotely. Communication and productivity tools included <span class="skill">GIT</span>, <span class="skill">Trello</span> and <span class="skill">Slack</span>.
<!--more-->
