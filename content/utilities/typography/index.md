---
title: Typography
url: /utilities/typography
menu:
  design_system:
    parent: Utilities
    weight: 10
type: doc
sidebar_menue_id: docs
---

The WVU Design System includes a number of utilities to style your content.

## Font Options

Font licenses can be purchased online. See [WVU’s typography guidelines](https://universityrelations.wvu.edu/brand-guide/type) for details.

## Example Type Hierarchy

User our typography and element utilities with Bootstrap’s text utilities to create a strong type hierarchy.

{{< readfile file="headless/hierarchy-business.html" >}}

{{< readfile-code file="headless/hierarchy-business.html" code="true" >}}

## Letter-Spacing and Line Height

You can combine the `wvu-text-spacing-wide` utility with Bootstrap’s `lh-lg` utility to adjust the line height and letter spacing of headings.

{{< readfile file="headless/tracked-helvetica-neue-black-condensed.html" label="Condensed Black Helvetica" >}}

{{< readfile-code file="headless/tracked-helvetica-neue-black-condensed.html" code="true" >}}

{{< readfile file="headless/tracked-iowan-old-style-black-italic.html" label="Iowan Black Italic" >}}

{{< readfile-code file="headless/tracked-iowan-old-style-black-italic.html" code="true" >}}

## Measure

## Outline and Shadow

You can add an outline to Oliviar Black when using Bootstraps’s `display-1` or `display-2` heading utilities. Just add the class `wvu-text-echo-outline` in your heading element. Make sure to add a `data-text=` attribute that repeats the content of your heading.

{{< readfile file="headless/display-heading-outline.html" label="Oliviar Black with Outline" >}}

{{< readfile-code file="headless/display-heading-outline.html" code="true" >}}

\* Only works with Webkit browsers.

{{< readfile file="headless/display-heading-outline-w-gradient.html" label="Oliviar Black with Gradient Outline" background_color="bg-dark" >}}

{{< readfile-code file="headless/display-heading-outline-w-gradient.html" code="true" >}}

### Echos

{{< readfile file="headless/oliviar-black-w-outline.html" label="Oliviar Black with Outline" >}}

{{< readfile-code file="headless/oliviar-black-w-outline.html" code="true" >}}

Add a shadow with `wvu-text-echo-shadow`.

{{< readfile file="headless/oliviar-black-w-outline-shadow.html" label="Oliviar Black with Outline and Shadow" >}}

{{< readfile-code file="headless/oliviar-black-w-outline-shadow.html" code="true" >}}