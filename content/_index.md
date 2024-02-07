---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  # - block: hero
  #   content:
  #     title: |
  #       Wei Xie Research Group
  #     image:
  #       filename: 1.png
  #     text: |
  #       <br>

  #       The **Wei Xie Research Group** has been a center of excellence for Automation research, teaching, and practice since its founding.



  - block: markdown
    content:
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

        <table class="table" width="850" border="0" align="center" cellspacing="0" cellpadding="5">
        <tbody><tr><td width="50%"   valign="middle"><img src="https://lecar-lab.github.io/assets/neural_swarm.gif" width="100%"></td><td width="50%"  valign="middle"><img src="https://lecar-lab.github.io/assets/neural_swarm.gif" width="100%"></td></tr></tbody></table>

        <table class="table" width="850" border="0" align="center" cellspacing="0" cellpadding="0"><tbody><tr><td width="100%"        valign="middle" style="padding-left: 5px; padding-right: 5px"><img src="https://lecar-lab.github.io/assets/cajun.gif" width="100%"></td></tr></tbody></table>

    design:
      spacing:
        padding: ["20px", "200px", "20px", "200px"]
  - block: markdown
    content:
      title: 👋 Welcome to the group
      text: |
        <span style="font-size: 1em;">
        Welcome to the Wei Xie Laboratory at Shanghai Jiao Tong University's Department of Automation! <br>The <b>Wei Xie Research Group</b> has been a center of excellence for Automation research, teaching, and practice since its founding. We are dedicated to advancing autonomous unmanned systems in marine and port environments. Led by Dr. Wei Xie, our team conducts cutting-edge research in <b>robust control</b>, <b>backstepping control</b>, and <b>motion control</b>. We collaborate with industry partners and welcome passionate students to join our research endeavors. Explore our website to learn more about our work.</br></span>
        

    design:  
      spacing:
        padding: ["20px", "200px", "20px", "200px"]
      background:
        # Choose a color such as from https://html-color-codes.info
        color: 'white'

  - block: collection
    id: publication
    content:
      title: | 
        Latest News
      subtitle:
      text:
      count: 5
      filters:
        folders:
          - post
        author: ''

      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '1'
      # flip_alt_rows: false
      background:
        # Choose a color such as from https://html-color-codes.info
        color: 'white'
      spacing:
        padding: ["20px", "200px", "20px", "200px"]

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ""
  #     text:
  #   design:
  #     columns: "1"
  #     background:
  #       image:
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ["20px", "0", "20px", "0"]
  #     css_class: fullscreen
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="test" >}}
  #   design:
  #     columns: '1'
  - block: markdown
    content:
      title: News
      subtitle:
      text: |
        - Jian Yang and Monica Hall Win the Best Paper Award at Wowchemy 2020
        - Richard Hendricks Wins First Place in the Wowchemy Prize
        - Congratulations to Jian Yang and Monica Hall for winning the Best Paper Award at the 2020 Conference
    design:  
      spacing:
        padding: ["20px", "200px", "20px", "200px"]
      background:
        # Choose a color such as from https://html-color-codes.info
        color: 'white'
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: "1"
      background:
        color: 'white'



      
---
