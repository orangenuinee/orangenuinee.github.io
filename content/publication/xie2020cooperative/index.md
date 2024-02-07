---
title: 'Cooperative Path Following Control of Multiple Quadcopters with Unknown External Disturbances'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 谢威
  - D. Cabecinhas
  - R. Cunha
  - C. Silvestre

# Author notes (optional)
author_notes:

date: '2020-11-12T00:00:00Z'
doi: '10.1109/TSMC.2020.3032401'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-11-12T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Systems Man Cybernetics-Systems*, 2020
publication_short: In *TSMC*

abstract: In this article, we address the task of cooperative path following control of multiple autonomous quadcopters in the presence of unknown external disturbances. Under the assumption that the communications among the vehicles are bidirectional and continuous, a synchronized path following strategy is proposed that regulates the speed of each vehicle along its path to reach consensus in relative position. Moreover, collision-free transient paths from the vehicle initial positions to a group of suitable selected positions along the desired paths are designed. Building on the backstepping technique, the proposed path following controller for each individual vehicle drives the quadcopter toward, and to stay within an arbitrarily small neighborhood of its corresponding desired path, achieving global uniformly ultimately boundedness. In addition, the devised controller guarantees that the actuations are bounded with respect to the position error. The controller is also made robust to external constant or slowly time-varying disturbances by the introduction of dynamic estimators for the disturbances. A projection operator is used to ensure that the estimates remain within the prescribed bounds and are sufficiently smooth to be backstepped. In order to validate the effectiveness and performance of the proposed methodology, we present and analyze both simulation and experimental results.

# Summary. An optional shortened abstract.
summary: This article presented a solution to the problem of CPF control of a group of underactuated autonomous quadcopters. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9257200'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
