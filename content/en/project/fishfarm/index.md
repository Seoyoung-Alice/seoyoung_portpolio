---
title: Development of FishFarm monitoring Application
summary: Android App with Bluetooth Communication for Smart Fish Farm Monitoring
tags:
- Android Application
- Monitoring
- Java
- Cpp
- Bluetooth
date: "2015-11-29T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Application main page
  focal_point: Smart

#links:
#- icon: github
#  icon_pack: fab
#  link: https://github.com/Seoyoung-Alice

url_code: "https://github.com/Seoyoung-Alice/FishFarm"
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
- Development of Android Application that can check and manage water quality sensor information of fish tank using Bluetooth in real time

##	Overview
- Period : Aug. 15 ~ Nov. 15 (4 months)
- Role : Design and Development Android Application

##	Project Content
- Communication between Water Quality Sensors and Applications using Bluetooth
- Receive sensor information in real time and output to application 
- Sensor control using the control command registered with the sensor
- Setting sensor basic information such as sensor offset, measurement cycle, etc.
- Store sensor information such as real-time time, water temperature, CHL, BGA, etc. in .csv file

##	Development Environment
- Android OS(Jelly Bean)
- Bluetooth 4.0 (BLE)
- Android Studio
- java
- CPP

##	Result
- Localization of products
- Development of prototype system for fish farm monitoring

{{< figure src="fishfarm_setting.png" title="setting page" lightbox="true" >}}
{{< figure src="fishfarm_file_save2.jpg" title="saving file" lightbox="true" >}}
{{< figure src="fishfarm_data_save_result.png" title="saving file result" lightbox="true" >}}