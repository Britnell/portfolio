---
title: "a webcomponent version of my scroll hook"
id: "scrollerwebc"
date: "21/3/2024"
tags: ["css", "scroll", "web components"]
button:
  {
    label: "code",
    url: "https://github.com/Britnell/astronomical/blob/main/public/scroller.js",
    icon: "git",
  }
---

a while ago i made some [react hooks](https://css-var-animate.netlify.app/) for scroll animations that leveraged css variables. now I wanted a platform agnostic version of this, that I built with vanilla web component.
[code on git](https://github.com/Britnell/astronomical/blob/main/src/pages/scroller/index.astro)

- intersection observer attaches 'onscroll' event listener only when visible, so it scales well and can be used for many elements on the same page
- 'scroll' event calculates scroll variables and attaches to element as css variable
