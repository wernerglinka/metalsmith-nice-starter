---
layout: blocks.njk
bodyClasses: "blocks-page"

seo:
  title: Metalsmith Bare-bones Starter
  description: "This starter should get you up and running with your new favorite static site genrator Metalsmith"
  socialImage: "/assets/images/metalsmith-starter-social.png"
  canonicalOverwrite: ""

sections:
  - component: row
    rowFields:
      disabled: false
      rowId: "section3"
      rowClass: "this-class"
      inContainer: true
      margin:
        top: false
        bottom: true
      padding:
        top: false
        bottom: false
      background:
        color: "#f5f5f5"
        image: ""
      
    columns:
      - column:
        blocks:
          - name: text
            title: And there is more
            header: "h1"
            subTitle: "what noch mehr?"
            prose: |-
              The starter is now using [Barba](https://barba.js.org/) to enable smooth and fluid page transitions. This feels a lot like a Single Page Application.
          - name: ctas
            ctas:
              - url: "/apple.com"
                label: "go to apple"
                isExternal: true
                isButton: true
                buttonStyle: "primary"
      - column:
        blocks:
          - name: image
            src: "v1664225765/company-starter/pexels-andrea-piacquadio-3846508_nhl2jk.jpg"
            alt: "nunjucks"
            aspectRatio: "66.67"
            caption: "Photo by Andrea Piacquadio from Pexels"
---
