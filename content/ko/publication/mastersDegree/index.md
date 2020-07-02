---
title: "선회와 상승을 고려한 무인항공기의 3차원 복합 비행경로 알고리즘 연구"
authors:
- admin
date: "2020-02-27T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-01-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "한국산업기술대학교 일반대학원"
publication_short: ""

abstract: "전 세계적으로 무인항공기 시장은 폭발적인 증가를 보여주고 있다. 또한
최근에는 농업, 서비스업 등 다양한 분야에 이용하고 있으며 특히
군사용으로는 감시, 정찰, 공격 등 다양한 임무에 활용되고 있다.
무인항공기의 성공적인 임무 수행을 위해선 지정된 지역까지 상대에게 적발
되지 않고 높이와 위력을 가지는 지형지물과 SAM-Site에 유의하면서
이동해야한다. 이에 따라 임무의 난이도가 급격하게 상승되어 사고율과 임무
실패율이 높아진다.
무인항공기의 임무 성공률을 높이기 위해 많은 연구기관에서 경로 선정과
관련한 다양한 알고리즘 및 시뮬레이션 연구결과를 제시하고 있다.
그러나 기존에 연구된 대부분의 무인항공기 경로 선정 알고리즘은 실제
무인항공기 임무에 적용하기 힘든 2차원 공간에서 경로 선정을 진행하고
있다. 또한 3차원 경로 선정 연구는 2차원 평면상에서의 경로 선정 후 수직
정보를 적용하거나 일정한 운항고도에서의 경로 선정을 이용하여 선회 또는
상승 비행 중 한 가지 비행방법만을 이용하므로 3차원 경로 선정이라고
표현하기 어렵다. 따라서 선회와 상승 비행 중 상황에 따라 효율적인 방법을
선정하는 복합 경로 선정이 필요하다. 본 논문에서는 3차원 공간에서
위협요소인 산, 협곡과 같은 지형지물과 SAM-Site의 위력을 복합적으로
고려하여 상황에 따라 무인항공기의 실제 비행 방법인 선회, 상승, 하강
비행에 맞춘 최적의 경로를 산출하는 알고리즘을 제시한다. 마지막으로
시뮬레이션 결과를 통하여 제안하는 알고리즘의 효용성 검증 결과를
제시한다."

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- 3차원 경로선정
- 알고리즘
- 무인항공기
- 보로노이 다이어그램
- 베지어 곡선
- MATLAB
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: "files/masters_thesis_uav_3d_pathplanning.pdf"
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- UAV_3D_pathplanning

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---