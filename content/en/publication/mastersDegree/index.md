---
title: "A Study on 3-Dimensional Combined Flight Path Algorithm for UAV Considering Turning and Elevation"
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
publication: "Graduate School Korea Polytechnic University"
publication_short: ""

abstract: "In this paper, The global market for unmanned aerial vehicles (UAV) is showing explosive growth. Moreover, UAVs are being actively used in various areas including the agriculture and service industries. For military purposes, UAVs perform diverse missions such as surveillance, reconnaissance and attacks. To successfully accomplish these missions, a UAV needs to travel to a designated point without being detected by opponents while keeping off the presence of high and obstructive geographic features and SAM sites. In these situations, the difficulty level of the mission drastically increases, which results in higher accident and failure rates.

<p>Many research institutes have presented various algorithms and simulation results regarding the determination of the UAV’s flight path in order to improve the success rate of missions.</p>

<p>However, most UAV flight path selection algorithms developed in existing studies selected a flight path in a two-dimensional space, which is hardly applicable to real UAV missions. Moreover, other studies on three-dimensional flight paths selected a path in a two-dimensional plane and then applied vertical information or examined either circling flight or ascending flight by applying paths at a constant flight altitude. Thus, these methods can hardly be regarded as selecting a flight path in a three-dimensional space. Consequently, a composite method to determine an efficient path for each flight mode (circling or ascending) is required.</p>

<p>This study proposes an algorithm that identifies optimal paths for a UAV’s real flight modes of circling, descending, and ascending by comprehensively analyzing three-dimensional risk factors such as geographic features (mountains, valleys, etc.) and SAM sites. Finally, the effectiveness of the proposed algorithm is verified through simulation results.</p>"

# Summary. An optional shortened abstract.
summary: A Study on the UAV 3D composite path selection algorithm considering flight modes of circling, descending, and ascending to improve mission success rate and efficient flight path selection for UAV

tags:
- 3D path planning
- Algorithm
- UAV(Unmanned Aerial Vehicle)
- Voronoi Diagram
- Bézier Curve
- MATLAB
featured: true

links:
 - name: "RISS"
   url: "http://www.riss.or.kr/search/detail/DetailView.do?p_mat_type=be54d9b8bc7cdb09&control_no=f64fdc500192cdb7ffe0bdc3ef48d419"

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