---
title: GPR 신호 획득률 개선을 위한 RTS 및 다중 ADC 설계
summary: Altera FPGA를 이용한 임베디드 SoC
tags:
- GPR
- RTS
- RF 신호 처리
- 다중 ADC
- Altera Cyclone
- FPGA
- 임베디드 SoC
- 졸업
date: "2017-04-21T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 200M RTS 데이터 중첩 블럭도
  focal_point: Smart

#links:
#- icon: github
#  icon_pack: fab
#  link: https://github.com/Seoyoung-Alice

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
- RTS 및 다중 ADC를 이용한 GPR 장비에서의 신호 수신 획득률 증가 및 속도 향상을 위한 임베디드 SoC 설계

##	개요
- 기간 : 15. 06 ~ 17. 04 (11개월)
- 역할 : UART를 이용한 통신 개발

##	프로젝트 내용
- GPR 장비의 송신기에서 보낸 UWB 신호가 장애물에 반사되어 돌아오는 신호를 통해 탐사하는 레이더
- GPR 수신기의 속도 향상과 유효 데이터 획득률을 높이기 위해 고속 샘플링 및 데이터 누적을 이용
- 수신 데이터의 고속 처리를 위해 ADC의 개수를 늘려 데이터 처리 속도 증가
- ADC를 이용한 수신 아날로그 신호 처리 시스템
- DPRAM을 이용한 데이터 Sync 조절
- UART 통신을 통한 컴퓨터 및 장비간의 데이터 전송

##	개발 환경
- VHDL
- Quartus
- Modelsim을 이용한 시뮬레이션
- Altera Cyclone Series

##	성과
- 학부 졸업작품 완성 및 결과 논문 개재
- GPR 장비의 성능 향상을 위한 고속 데이터 처리 프로토 시스템 개발

{{< figure src="graduation_diagram.jpg" title="시스템 모식도" lightbox="true" >}}
{{< figure src="graduation_hw.jpg" title="시스템 하드웨어" lightbox="true" >}}
{{< figure src="graduation_200M_simulation_result_1.jpg" title="200M 시뮬레이션 결과 1" lightbox="true" >}}
{{< figure src="graduation_200M_simulation_result_2.jpg" title="200M 시뮬레이션 결과 2" lightbox="true" >}}
{{< figure src="graduation_200M_RTS_result_mathlab.jpg" title="200M RTS 결과(by MATLAB)" lightbox="true" >}}
{{< figure src="graduation_result_osil.jpg" title="신호 측정 결과(by 오실로스코프)" lightbox="true" >}}