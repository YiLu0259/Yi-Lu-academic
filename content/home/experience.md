---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100

title: Experience
subtitle:
    
# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006
    
# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Assistant
    company: Bronfenbrenner Center, Cornell University
    company_url: 'https://www.human.cornell.edu/people/kap6'
    location: NY, US
    date_start: '2023-08-21'
    date_end: '2023-12-01'
  
  - title: Research Assistant
    company: Lifespan Developmental Lab, Peking University
    company_url: 'https://www.psy.pku.edu.cn/english/people/faculty/associate_professor/xinzhang/index.htm'
    location: Beijing, China
    date_start: '2017-09-01'
    date_end: '2020-07-01'
    description: |2-
        
        * Undergraduate research on the impact of aging stereotypes on older people’s risky decisions
        * Honor thesis on a cross-cultural comparison study of Chinese and Americans' self-continuity across age

  - title: Research Assistant
    company: Perception, Action & Cognition Lab, Brown University
    company_url: 'https://research.clps.brown.edu/songlab/'
    location: RI, US
    date_start: '2019-06-26'
    date_end: '2019-09-01'
    description: |2-
    
        * Designed and conducted action experiments using Sketchup, MATLAB Psychtoolbox and movement tracking pad. 
        * Analyzed data on hand movement trajectory and reaction performance using MATLAB. 

    
  - title: Research Assistant
    company: Affective Science and Culture Lab, Yale University
    company_url: 'https://asclab.yale.edu/'
    location: CT, US
    date_start: '2019-07-01'
    date_end: '2019-10-01'
    description: Conducted natural language meaning analysis using Meaning Extraction Helper and ZhToken.

design:
  columns: '2'
  background:
    # Name of image in `assets/media/`.
    image: Gallery.jpeg
    # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
    image_darken: 0.4
    #  Options are `cover` (default), `contain`, or `actual` size.
    image_size: cover
    # Options include `left`, `center` (default), or `right`.
    image_position: center
    # Use a fun parallax-like fixed background effect on desktop? true/false
    image_parallax: true
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: true  
---
