---
title: "A novel S-shape based NURBS interpolation with acc-jerk-Continuity and round-off error elimination"
authors:
- Yifei Hu

- Xin Jiang
- Guanying Huo
- Cheng Su
- admin
- Hexiong Li
- Zhiming Zheng
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2021-03-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2103.14433"
publication_short: ""

abstract: Feedrate scheduling is a key step in computer numerical control (CNC) machining, as it has a close relationship with machining time and surface quality, and has now become a hot issue in industry and academia. To reduce high chord errors and round-off errors, and generate continuous velocity, acceleration, and jerk profile of parametric interpolation, a novel and complete S-shape based feedrate scheduling algorithm is presented in this paper. The algorithm consists of three modules - bidirectional scanning module, velocity scheduling module and round-off error elimination module. The bidirectional scanning module with the limitations of chord error, normal acceleration/jerk and command feedrate aims to guarantee the continuity of the feed rate at the junctions between successive NURBS sub-curves. After the NURBS sub-curves have been classified into two cases, the velocity scheduling module firstly calculates the actual maximum federate, and then generates the feed rate profiles of all NURBS sub-curves according to our velocity scheduling function. Later, the round-off error elimination module is proposed to make the total interpolating time become an integer multiple of the interpolation period, which leads to the elimination of round-off errors. Finally, benchmarks are conducted to verify the applicability of the proposed method compared with some other methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
