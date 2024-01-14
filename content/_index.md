---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: Read my most recent paper on LLMs in Ophthalmology
          icon: academicons/pubmed
          url: https://pubmed.ncbi.nlm.nih.gov/37923374/
        - text: Read my most cited paper in 2023
          icon: academicons/elsevier
          url: https://www.ophthalmologyscience.org/article/S2666-9145(23)00056-8/fulltext
        - text: Watch my Valedictory Speech 5 Tips for MD Graduates 
          icon: brands/youtube
          url: https://youtu.be/Mbzujce_JJU?si=DbF5XtKTFITjBQpb
        - text: Watch my scientific talks on YouTube
          icon: brands/youtube
          url: https://youtube.com/playlist?list=PLK4ymmNyRHh4DUMCyb3jiMN1QmFrfUENl&si=cEfenGsUdUpsrrcI
---