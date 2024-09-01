---
title: Backgrounds
menu:
  design_system:
    parent: Utilities
    weight: 40
type: doc
---

Background are handled differently in Version 3. In prior versions, background images would be applied via CSS to the container element of a component. Now images are put in the DOM so we can use different image files depending on browser width, which enables us to create more performant websites. Other background elements are also layered on top of the image rather than...

To use... wrap all background elements using the `wvu-bg-img` utility.

## Filters