---
title: 'Adaptive Backstepping Control of a Quadcopter with Uncertain Vehicle Mass, Moment of Inertia, and Disturbances'

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

date: '2021-02-02T00:00:00Z'
doi: '10.1109/TIE.2021.3055181'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-02-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *IEEE Transactions on Industrial Electronics*, 2021
publication_short: In *IEEE TIE*

abstract: In this article, we propose a solution to the problem of path following for a quadcopter aircraft with unknown vehicle parameters (mass and moment of inertia) and external disturbances. By employing the backstepping technique, the proposed adaptive control strategy guarantees the following. The quadcopter is globally steered toward, and kept within, an arbitrarily small neighborhood of a desired smooth path, achieving global uniformly ultimately boundedness; compared to trajectory tracking, a smoother convergence is obtained as the control actuation signals (thrust force and torque) are bounded with respect to the position error, and the designed timing law ensures that the desired path starts to move only when the vehicle gets close to the desired path; and a single adaptive control law can be used for accurate motion control of aerial vehicles with a wide range of inertial properties, without the need for retuning control gains or other parameters. Moreover, the controller is also made robust to external constant and slowly time-varying disturbances through the design of disturbance estimators. To demonstrate the effectiveness and performance of the proposed control strategies, simulation and experimental results are presented and analyzed.

# Summary. An optional shortened abstract.
summary: Building on the backstepping technique, this article presented a control strategy to stabilize an underactuated quadcopter along a predefined path in the presence of uncertain vehicle mass, moment of inertia, and external disturbances. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9345483'
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
