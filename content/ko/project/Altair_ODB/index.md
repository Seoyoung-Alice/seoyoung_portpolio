---
title: Export to ODB++
summary: Altair PollEx의 PDBB를 Valor사의 ODB++ 파일로 출력
tags:
- Cpp
- MFC
- Windows Application
- Altair-EDA
date: "2020-11-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Export ODB Functions
  focal_point: Smart

url_code: ""
url_pdf: "ko/files/Expand_Shrink_Algorithm.pdf"
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
- valor 사의 ECAD 구조 분석을 통한 자사 PDBB파일을 ODB++ 파일로 변환하는 기능 개발

##	개요
- 기간 : 20. 11 ~ 21.03 (5개월)
- 역할 : ODB++ 변환 개발 및 알고리즘 개발

##	프로젝트 내용
- valor 사의 ECAD 구조 분석하여 ODB++ 파일로 변환하여 출력하는 기능개발
- PCB 구조 분석 및 자사 ECAD 구조인 PDBB 구조 분석
- 기존 Expand, Shrink 알고리즘 방식이 동작시간이 오래걸리는 단점 및 곡선이 Line으로 나오는 단점 보완을 위한 알고리즘 개발

##	개발 환경
- C++
- MFC
- Visual Source Safe

##	성과
- 신규 기능인 ODB++ 출력 추가
- 기존 Expand, Shrink 알고리즘 대비 90% 연산 속도 향상 및 곡선을 보존 시키는 알고리즘 완성

{{< figure src="ExportODB_Process.png" title="Export ODB Process" lightbox="true" >}}
{{< figure src="ExportODB_Result.png" title="Compare with Export ODB Result" lightbox="true" >}}
