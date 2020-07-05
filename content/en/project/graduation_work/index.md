---
title: RTS and multiple ADC designs to improve GPR signal acquisition rates
summary: Embedded SoC using Altera FPGA
tags:
- GPR
- RTS
- RF signal processing
- Multiple ADCs
- Altera Cyclone
- FPGA
- Embedded SoC
- Graduation work
date: "2017-04-21T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 200M RTS data overlaid system block diagram
  focal_point: Smart

#links:
#- icon: github
#  icon_pack: fab
#  link: https://github.com/Seoyoung-Alice

url_code: "https://github.com/Seoyoung-Alice/GPR_system"
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
- Embedded SoC Design for Increasing Signal Receiving Rate and Speed in GPR Equipment Using RTS and Multiple ADCs

##	Overview
- Period : Jun. 15 ~ April. 17 (11 months)
- Role : Development of Communication Using UART

##	Project Content
- Radar that probes UWB signals from transmitters on GPR equipment through signals that reflect back on obstacles
- Utilize high-speed sampling and data accumulation to speed up GPR receivers and increase effective data acquisition rates
- Increase the speed of data processing by increasing the number of ADCs for fast processing of incoming data
- Incoming Analog Signal Processing System Using ADC
- Data Sync Adjustment with DPRAM
- Transmitting data between computers and equipment via UART communication

##	Development Environment
- VHDL
- Quartus
- Simulation with Modelsim
- Altera Cyclone Series

##	Result
- Completion of undergraduate graduation work and publication of result papers
- Development of High-Speed Data Processing Prototype System to Improve Performance of GPR Equipment

{{< figure src="graduation_diagram.jpg" title="system diagram" lightbox="true" >}}
{{< figure src="graduation_hw.jpg" title="target H/W" lightbox="true" >}}
{{< figure src="graduation_200M_simulation_result_1.jpg" title="200M simulation result 1" lightbox="true" >}}
{{< figure src="graduation_200M_simulation_result_2.jpg" title="200M simulation result 2" lightbox="true" >}}
{{< figure src="graduation_200M_RTS_result_mathlab.jpg" title="200M RTS result(by MATLAB)" lightbox="true" >}}
{{< figure src="graduation_result_osil.jpg" title="signal measurement result(by oscilloscope)" lightbox="true" >}}