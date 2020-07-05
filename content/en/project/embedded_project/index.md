---
title: 임베디드 리눅스를 이용한 색상 맞추기 게임
summary: device driver 및 Makefile 설계를 통한 리눅스를 이용한 임베디드 시스템 개발
tags:
- 임베디드
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
  caption: 게임 화면
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

##	요약
- 제한 시간 안에 랜덤으로 나오는 색상을 순서대로 누르는 게임

##	개요
- 기간 : 16. 10 ~ 16. 11 (2개월)
- 역할 : 팀장 / frame buffer 이용하여 이미지 제어 및 Touch LCD device driver 설계

##	프로젝트 내용
- Touch LCD의 랜덤 위치에 랜덤 색상이 나오도록 함
- 제한 시간안에 못하거나 틀리면 무서운 사진과 함께 부저가 울림
- Linux 디바이스 driver를 이용하여 buzzer, button, touch LCD 등 제어
- touch LCD, buzzer 등 장치의 device driver 설계 & Makefile 개발

##	개발 환경
- Arm Cortex-A9 기반 장비
- Linux Ubuntu
- C, CPP

##	성과
- 임베디드 software를 통해 Linux의 이해 및 device driver, Makefile 개발의 기초 마련
- 기존의 Sample device driver, Makefile을 분석하고 응용하여 개발
- 각 장치 및 target device의 성능 구조를 이해하여 기능 구현

{{< figure src="embedded_3.jpg" title="색상 맞추기 게임 화면" lightbox="true" >}}
{{< figure src="embedded_4.jpg" title="게임 인터페이스" lightbox="true" >}}
{{< figure src="embedded_5.jpg" title="게임 오버" lightbox="true" >}}