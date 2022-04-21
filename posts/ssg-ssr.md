---
title: 'TailwindCSS: My new found love for CSS'
date: '2022-04-26'
---

I highly recommend using **TailwindCSS**. 

TailwindCSS is a CSS framework that is used to style elements in your app. It is a _pre-built_ library that comes with a bunch of classes that you can use in your CSS.

If you want to resuse styles (i.e. a wrapper to constrain large content), you can use **@apply** in your globals.css file.

@layer components {
    .wrapper {
        @apply mx-auto w-11/12 max-w-screen-xl p-8;
    }
}

This is the same as writing out: margin: 0 auto, width: 91.666667:, max-width: 1280px. A wrapper is generally between 1000px - 1300px.