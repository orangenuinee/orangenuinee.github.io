---
# Page title
title: My page
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: Research
      subtitle: recently
      text: |
        <style>
          .table {
            border-collapse: collapse;
            margin-bottom: 0px;
            margin-top: 0px;
            padding-bottom: 0px;
            padding-top: 0px;
            line-height: 0.5
            border-spacing: 0px
          }
          .table td,
          .table th {
            border: none;
          }
        </style>
        ### Safe Learning-based Nonlinear Control with Learned Robotic Agility
        <div style="display: flex; justify-content: center; align-items: center; margin-bottom: 5px; margin-top: 5px">
          <img src="https://lecar-lab.github.io/research/safe_learning_control.png" width="50%">
        </div>

        <p>Real-world robotic systems have to operate in unknown and dynamic environments where the decision-maker must fast adapt to uncertainties. For example, legged robot rescue and search necessitates traversing complicated terrain conditions. Deep learning has representation power but is often too slow to update onboard. On the other hand, adaptive control can update as fast as the feedback control loop with guarantees. Our goal is to develop offline and online algorithms that can effectively learn from offline data and efficiently fine-tune/adapt in real time.</p>
        <br>  

        ### Offline Learning and Online Adaptations
        <div style="display: flex; justify-content: center; align-items: center;">
          <img src="https://lecar-lab.github.io/research/adaptive.png" width="50%">
        </div>

        <p>Real-world robotic systems have to operate in unknown and dynamic environments where the decision-maker must fast adapt to uncertainties. For example, legged robot rescue and search necessitates traversing complicated terrain conditions. Deep learning has representation power but is often too slow to update onboard. On the other hand, adaptive control can update as fast as the feedback control loop with guarantees. Our goal is to develop offline and online algorithms that can effectively learn from offline data and efficiently fine-tune/adapt in real time.</p>

    design:
      spacing:
        padding: ["20px", "300px", "20px", "300px"]

---