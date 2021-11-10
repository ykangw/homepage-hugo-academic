---
title: Integration of RTK, IMU and visual SLAM for Outdoor Robot Navigation
summary: Master thesis
tags:
- GeoAI
- Localization
date: "2021-09-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Funded by European Research Council (ERC).
#   focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

This my master dissertation, supervised by [Dr Daniel Freer](https://scholar.google.co.uk/citations?user=waOzSEQAAAAJ) (Antobot) and [Dr Philippa J Mason](http://www.imperial.ac.uk/people/p.j.mason/research.html) (Imperial College London).

Accurate position and pose estimation are the foundations of autonomous robotics, which usually rely on the fusion of multiple sensors. In this project, we introduced a sensor fusion method based on an extended Kalman filter using Robot Operating System (ROS) for robot outdoor localization, which supports many sensors of different types and can be used both in real-time and offline. Stereo visual SLAM, an IMU and a dual-frequency RTK GNSS on the robot are fused in the experiments to achieve robust and precise ego-motion tracking. Loop closure localization accuracy using different combinations of sensors are evaluated and analysed. An average error of less than a centimetre is achieved by fusing these three sensors.
