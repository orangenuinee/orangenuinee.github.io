---
title: "Saturated Backstepping-Based Tracking Control of a Quadrotor With Uncertain Vehicle Parameters and External Disturbances"
authors:
- 谢威
- Weidong Zhang
- Carlos Silvestre
author_notes:
date: "2021-08-21T00:00:00Z"
doi: "10.1109/LCSYS.2021.3129891"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-11-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE CONTROL SYSTEMS LETTERS*, 2021"
publication_short: "*L-CSS*"

abstract: Knowing the vehicle’s parameters (e.g., mass, moment of inertia) in advance is not always possible in quadrotor control applications, especially if we use the quadrotor for cargo transportation. Uncertain cargo weight and size together with external disturbances may result in closed-loop performance degradation or even instability. In light of this problem, this letter proposes a saturated robust adaptive tracking controller for a quadrotor based on nonlinear Lyapunov-theory, where a set of estimation laws are designed to compensate for uncertain parameters and disturbances, achieving global uniformly ultimately boundedness (GUUB). Additionally, through the use of saturation functions, the designed thrust force is ensured to be bounded by a predefined value. Numerical simulation examples are presented and discussed to validate the effectiveness of the proposed solution. To further highlight the enhancements of the presented method, comparison results with an existing control strategy are provided and analyzed.

# Summary. An optional shortened abstract.
summary: This letter proposed a solution to the trajectory tracking control problem with application to an underactuated quadrotor, guaranteeing that the vehicle was able to track its desired trajectory with arbitrarily small position error. 

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
slides: example
---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
