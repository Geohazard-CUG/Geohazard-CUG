---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
      image:
        filename: welcome.jpg
      text: |
        <br>
        欢迎来到中国地质大学（武汉）灾害信息地理课题组。我们专注于融合地理信息科学、测绘遥感和工程地质的多学科知识提升地质灾害风险的主动防范能力。课题组长期致力于应用空间信息、多源遥感和人工智能等技术开展地质灾害风险的早期识别、量化表征和预警预报等，与University collage London、University of Exeter，GFZ，University of Florence，University of Padova等研究机构的学术团队建立了长期广泛的交流合作，共同推进地质灾害风险研究与实践的国际交流与合作。
  
  - block: collection
    content:
      title: 新闻动态
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
