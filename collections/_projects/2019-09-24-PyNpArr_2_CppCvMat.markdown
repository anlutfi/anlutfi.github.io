---
layout: post
title: Sending OpenCV Images between Python and C++
description: A tool to send OpenCV images from Python to C++ and vice-versa, making it easier to run C++ OpenCV code from a Python console
date:   2019-09-24 16:48:09 -0200
categories: [portfolio, shareable]
permalink: PyNpArr2CppCvMat
excerpt_separator: 
image: 
thumb:
---
PyNpArr_2_CppCvMat is a simple interface to send <span class = "skill">OpenCV</span> images from <span class = "skill">Python</span> to <span class = "skill">C++</span> and vice-versa

<span class = "skill">OpenCV</span> code in <span class = "skill">Python</span>, although practical to write, can run quite slowly. Pixel-wise operations, if not done inside <span class = "skill">OpenCV</span>'s calls, can make real-time applications impossible.

On the other hand, while it runs much faster, <span class = "skill">C++</span> code can be quite a pain to debug, due to the lack of a practical console.

Implementing the heavy part in <span class = "skill">C++</span> and running it from <span class = "skill">Python</span> is the best of both worlds.

While sending basic types and data structures between the two is easy, sending images is not. This tool focuses on this specific problem. Although there are solutions that could handle the task -such as Boost- they tend to be quite bulky. This code was written using the ctypes <span class = "skill">Python</span> package, which is in its standard distribution.

[Source (Python and C++)](https://github.com/anlutfi/PyNpArr_2_CppCvMat){:target="_blank"} (requires [OpenCV](http://opencv.org/){:target="_blank"})

