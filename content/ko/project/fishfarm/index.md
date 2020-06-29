---
title: 양식장 모니터링 앱 개발
summary: An example of using the in-built project page.
tags:
- 3차원 경로선정 알고리즘
- 무인항공기
- MATLAB
- 석사학위논문
#date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 양식장 어플 메인화면
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

##	요약
- Bluetooth를 이용한 양식장 수조의 수질센서 정보를 실시간 확인 및 관리 할 수 있는 Android Application

##	개요
- 기간 : 15. 08 ~ 15. 11 (4 개월)
- 역할 : Android Application 디자인 & 프로그램 개발

##	프로젝트 내용
- Bluetooth를 이용한 수질센서와 Application간의 통신
- 실시간으로 센서정보를 받아 Application에 출력 
- 센서에 등록된 제어 command를 이용한 센서 제어
- 센서 offset, 측정 주기 등 센서 기본정보 설정
- 실시간 센서 정보를 시간, 수온, CHL, BGA 등 센서 정보를 .csv 파일로 저장

##	개발 환경
- Android OS(Jelly Bean)
- Bluetooth 4.0 (BLE)
- Android Studio
- java
- CPP

##	성과
- 해외 제품의 국산화
- 모니터링을 위한 프로토 타입 시스템 개발

{{< figure src="fishfarm_file_save2.jpg" title="양식장 어플 파일 저장화면" lightbox="true" >}}
{{< figure src="fishfarm_data_save_result.jpg" title="양식장 어플 파일 저장 결과" lightbox="true" >}}