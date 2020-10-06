---
title: NuxtChild Component
description: How to use the Nuxt Child component to create parent and child pages.
position: 39
category: examples
csb_link: https://codesandbox.io/embed/github/nuxt-academy/guides-examples/tree/master/03_features/09_components_nuxt
---

- `pages/parent.vue` contains the `<NuxtChild>` component. Everything on this page will be seen on both the parent and child pages.
- `pages/parent/index.vue` contains text that will be replaced when the child links are clicked.
- `pages/parent/child.vue` and `pages/parent/child2.vue` will be rendered as parent/child and parent/child2.

<base-alert type="next">

Learn more in the Features book in the [Nuxt Components](/guides/features/nuxt-components#the-nuxtchild-component) chapter.

</base-alert>

<code-sandbox :src="csb_link"></code-sandbox>