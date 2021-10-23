---
title: Example Project
summary: Design and Implementation of Transmission Line Defect Detection and Alarm System Based on Airborne with Jetson Nano
tags:
- Deep Learning
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

In recent years, due to the development of drone technology and the diversification of application scenarios, the use of drones for power inspection has become a hot research object. With the mobility and portability of drones, it is expected to achieve safety, efficiency, and intelligence. Inspection of power lines. 

There are two main tasks in this paper. 1. it is proposed to use the latest Yolov5 object detection algorithm for transmission line defect detection, and to independently label the undisclosed transmission line data set (a total of 3393 pictures) to train the Yolov5 model, and deploy the model on Jetson Nano. In the test, it is carried on the drone for testing to achieve a detection speed of 32fps and an accuracy of 96%. 2. Design and implement an alarm message push mechanism for interaction between the onboard Jetson Nano and the server, and then develop a transmission line defect detection alarm system. The system is equipped with an intuitive alarm visualization interface to support offline detection and online detection. 

This system provides a complete and intelligent platform for transmission line defect detection, which is an important step towards the realization of intelligent transmission line inspection.

 

**Keywords:** power inspection, defect detection, Jetson Nano, UAV, Yolov5