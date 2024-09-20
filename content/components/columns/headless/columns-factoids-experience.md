---
title: Columns with Factoids - WVU Experience Vibe
weight: 10
content_blocks:
  - _bookshop_name: section/columns
    elements:
      background_image:
        src: 
        alt:
      super_heading:
        icon: "location-dot"
        label: "Label"
        text: "Super Heading"
      heading: "Hello, world!"
      subheading: "Subheading"
      lead: "Lead text."
      copy: "Copy."
      columns:
      - column_blocks:
        - _bookshop_name: column/heading
          text: Great Outcomes.
        config:
          column_widths:
            xxl: col-xxl-12
      - column_blocks:
        - _bookshop_name: column/stat
          elements:
            pre: Did you know
            stat: 93%
            post: Postscript
            source: My Source
          styles:
            stat:
              font: oliviar-black
              size: display-2
              color: text-wvu-gold
        - _bookshop_name: column/stat
          elements:
            pre: Did you know
            stat: 93%
            post: Postscript
            source: My Source
          styles:
            stat:
              font: oliviar-black
              size: display-2
              color: text-wvu-gold
        config:
          column_widths:
            xxl: col-xxl-6
          text_align: text-center
      - column_blocks:
        - _bookshop_name: column/stat
          elements:
            pre: Did you know
            stat: 94%
            post: Postscript
            source: My Source
          styles:
            stat:
              font: oliviar-black
              size: display-2
              color: text-wvu-gold
        config:
          column_widths:
            xxl: col-xxl-6
          text_align: text-center
    config:
      is_main: false
      id: "hero"
      aria_labelled_by: "hero"
    layout:
      is_fluid: false
      align: "start"
      padding_y: "py-8"
    styles:
      vibe: 
      section:
        background_color: "bg-dark"
        text_color: "text-white"
      background_layers:
        photo:
          blend_mode:
          filter:
          value:
        pattern:
          option: "wvu-bg-topo-dark"
          color: "bg-dark"
          blend_mode:
          opacity:
        texture:
          color: "wvu-bg-texture"
          blend_mode:
      super_heading:
        label:
          font: "wvu-shout"
          case:
          color: "text-wvu-gold"
        text:
          font: "helvetica-neue-light"
          color: 
          tracking: 
      heading:
        font: "wvu-shout"
        color: 
        decoration: "wvu-bar"
      subheading:
        font: "helvetica-neue-bold"
        size: "h1"
        weight: 
      lead:
        font: "helvetica-neue-light"
        size: "fs-3"
      copy:
        font:
---

Test