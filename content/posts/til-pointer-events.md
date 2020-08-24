---
title: "#TIL - CSS Property to disable JS click events"
date: 2020-08-11 16:56:54
categories: life
tags: [ "css" ]
keywords: 
---

It doesn't really block/disable click events in JS but hides the element from a mouse click. This prevents interaction with the JS.

`pointer-events: none`

[pointer-events](https://developer.mozilla.org/en-US/docs/Web/CSS/pointer-events)

> The element is never the target of pointer events; however, pointer events may target its descendant elements if those descendants have `pointer-events` set to some other value. In these circumstances, pointer events will trigger event listeners on this parent element as appropriate on their way to/from the descendant during the event capture/bubble phases.

