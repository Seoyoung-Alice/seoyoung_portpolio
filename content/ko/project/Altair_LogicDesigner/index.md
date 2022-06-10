---
title: PollExLogicDesigner 프로그램 개발
summary: Schematic Design을 위한 Altair PollExLogicDesigner 제품 개발
tags:
- Cpp
- MFC
- Windows Application
- Altair-EDA
date: "2021-03-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: PollExLogicDesigner
  focal_point: Smart

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
- Logic Design을 위한 사내 신규 제품 개발

##	개요
- 기간 : 21. 03 ~ 현재 (약 1년 3개월)
- 역할 : 프로그램 템플릿 설계, ECAD 자료구조 변환, Picking 기능, Undo/Redo 기능 작업

##	프로젝트 내용
- Schematic Design을 위한 신규 제품인 PollExLogicDesigner 프로그램 개발
- PollExLogicDesigner 프로그램 템플릿 설계
- SDBB <-> UDF 라는 사내 ECAD 자료구조간 변환하여 파일 출력하는 기능 개발
- Mouse Event 처리인 Picking을 통한 수정 기능 개발
- Undo/Redo 구조 및 기능 개발
- Part의 속성을 Generic Symbol로 변환하는 기능 개발
- 그 외 프로그램 테스트 및 버그 수정

##	개발 환경
- C++
- MFC
- DirectX
- GitLab

##	성과
- Proptotype Revision, version 1.0 release

{{< figure src="LogicDesigner_Drag.png" title="LogicDesigner Drag" lightbox="true" >}}
