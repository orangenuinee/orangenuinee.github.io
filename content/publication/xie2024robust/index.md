---
title: 'Robust Collision-free Formation Control of Quadrotor Fleets: Trajectory Generation and Tracking with Experimental Validation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - 谢威
  - G. Yu
  - D. Cabecinhas
  - C. Silvestre
  - W. Zhang
  - W. He

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-02T00:00:00Z'
doi: 'https://doi.org/10.1016/j.conengprac.2024.105842'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Control Engineering Practice*
publication_short: In *CEP*

abstract: This paper addresses the problem of formation control of multiple quadrotor vehicles, focusing on ensuring inter-vehicle collision avoidance in the presence of time-varying external disturbances. The problem is divided into two sub-problems (i) the generation of collision-free trajectories; and (ii) trajectory tracking. Initially, by employing the Lyapunov-based backstepping technique, a set of collision-free trajectories is generated based on a potential function. Additionally, a trajectory tracking controller is developed for each individual quadrotor, ensuring accurate tracking of their respective trajectories. Furthermore, to attain robust tracking performance, nonlinear disturbance observers are developed and incorporated into the control inputs to compensate for time-varying external disturbances. Comprehensive simulation and experimental results are provided and analyzed to demonstrate the effectiveness and performance of the proposed strategy.

# Summary. An optional shortened abstract.
summary: In this paper, we have presented a comprehensive collision-free formation control strategy for a fleet of quadrotors. By introducing a novel potential function and leveraging Lyapunov-based control theory, we have successfully generated collision-free trajectories. Additionally, to ensure precise trajectory tracking, we have developed a nonlinear trajectory tracking controller for each individual quadrotor. The incorporation of a disturbance observer has enabled robust performance by compensating for external time-varying disturbances.   The effectiveness of the proposed control method has been demonstrated through extensive simulation and experimental results. The obtained outcomes validate the capability of our strategy in achieving collision-free formations and accurate trajectory tracking for quadrotor systems.   Future directions for research include extending our findings to address the time-varying formation control problem and considering the presence of dynamic obstacles. Furthermore, exploring optimized path planning techniques that take into account the vehicles’ kinematic and dynamic constraints would be an intriguing direction to pursue. These advancements will further enhance the capabilities of quadrotor systems in various applications and open new avenues for exploration in the field of formation control.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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
