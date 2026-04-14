# Hugo Site for Structure & Sense Journal

Some custom styling info:

```
{{< typing speed="50" pause="600" >}}
Welcome to <em>Structure & Sense: A Journal of Meaning, Organization, and Technology</em>.
Explore our <em>stories</em>.
Find <span class="highlight">your</span> next idea.
{{< /typing >}}
```

You can force pages into the site header with 

```
---
title: "Editorial Team"
slug: "team"
layout: "team"
menu:
  main:
    name: "Team"
    weight: 25
---
```