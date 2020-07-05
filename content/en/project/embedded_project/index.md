---
title: Snatch! Colors!(made with embedded Linux)
summary: Development of Embedded System using Linux through device driver and Makefile design
tags:
- Embedded
- Linux
- Makefile
- device driver
- Arm Core
- C
- Cpp
date: "2016-11-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: In Game
  focal_point: Smart

#links:
#- icon: github
#  icon_pack: fab
#  link: "https://github.com/Seoyoung-Alice"

url_code: "https://github.com/Seoyoung-Alice/Embedded_Linux_Game"
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

##	Summary
- A game that presses random colors in order within the time limit

##	Overview
- Period : 16. 10 ~ 16. 11 (2 months)
- Role : Team Leader(coordinate the duration, encourage team member) / merge programs / Control Touch LCD Image with Frame Buffer

##	Project Content
- The touch LCD displays random colors at random locations
- Buzzer sounds with scary pictures if not within the time limit or incorrect
- Use Linux device driver to control buzzer, button, touch LCD, etc.
- Design & Makefile Development of device driver for touch LCD, buzzer, etc.

##	Development Environment
- Arm Cortex-A9 Based Equipment
- Linux Ubuntu
- C, CPP

##	Result
- Studying a foundation for understanding Linux and developing device drivers and makefile
- Analyze and apply the sample device driver and makefile to develop
- Implementing functions by understanding the performance structure of each device and target device

{{< figure src="embedded_3.jpg" title="Game screen" lightbox="true" >}}
{{< figure src="embedded_4.jpg" title="Game interface" lightbox="true" >}}
{{< figure src="embedded_5.jpg" title="when Game Over" lightbox="true" >}}