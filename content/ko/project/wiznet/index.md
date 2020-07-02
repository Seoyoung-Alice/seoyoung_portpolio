---
title: Smart Study Room IoT 시스템
summary: IoT를 이용한 스마트 스터디 룸 시스템
tags:
- IoT
- Arm Core
- W7500
- Wiznet
- C
- Cpp
date: "2015-10-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 시스템 모식도
  focal_point: Smart

url_code: "https://github.com/Seoyoung-Alice"
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
- 공부하기 좋은 환경을 만들어주는 Smart 공부방 IoT 시스템 개발

##	개요
- 기간 : 15. 06 ~ 15. 10(약 5개월)
- 역할 : 팀장(기간 조율 및 팀원 독려) / relay 제작 및 제어, 프로그램 병합

##	프로젝트 내용
- Arm Core 기반의 W7500 보드와 센서들을 이용하여 유선 네트워크로 연동되는 IoT 시스템 구현
- 다양한 센서를 target board인 W7500(Arm Core 기반)으로 제어하여 자동으로 온도, 습도 등 집중하기 좋은 환경으로 맞춰 줄 수 있도록 함.
- 지정된 온도, 습도 값 유지를 위한 온습도 값에 따른 선풍기, 일조량 등 제어
- 모션센서를 이용한 이용자 유무 판별
- 유선 네트워크를 통한 컴퓨터로 원격 제어 기능

##	개발 환경
- Arm Core 기반의 W7500 보드
- mBed
- html
- CPP

##	성과
- Smart 공부방 IoT 시스템 개발
- 위즈네트 IoT 시스템 구현 대회 참가

{{< figure src="wiznet_1.jpg" title="사용 센서" lightbox="true" >}}
{{< video src="wiznet_result.mp4" controls="yes" >}}