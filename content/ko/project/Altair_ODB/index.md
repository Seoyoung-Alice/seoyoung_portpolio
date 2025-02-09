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
- ECAD 구조 분석을 통한 자사 UDF, PDBB파일을 ODB++ 파일로 변환하는 기능 개발

##	개요
- 기간 : 20. 11 ~ 21.03 (5개월)
- 역할 : ODB++ 변환 개발 및 알고리즘 개발

##	프로젝트 내용
- C++을 이용한 Polygon Expand, Shrink 알고리즘 개발
- UDF, PDBB, ODB++ 자료구조 분석
- ODB++ 자료구조 관리를 위한 C++ 클래스 구조 작업 follow-up
- UDF, PDBB 자료구조를 ODB++ 자료구조에 맞추어 변환하여 출력하는 기능 개발

##	개발 환경
- C++
- MFC
- Visual Source Safe

##	성과
- 곡선을 보존하는 Polygon Expand, Shrink 알고리즘 개발
- 기존 알고리즘 대비 90% 시간 단축
- 전세계 ODB++사용자 5만 이상의 잠정적 고객 확보

{{< figure src="ExportODB_Process.png" title="Export ODB Process" lightbox="true" >}}
{{< figure src="ExportODB_Result.png" title="Compare with Export ODB Result" lightbox="true" >}}
