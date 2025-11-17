# Hugo Site for Structure & Sense Journal

Some custom styling info:

```
{{< typing speed="50" pause="600" >}}
Welcome to the <strong>site</strong>.<br>
Explore our <em>stories</em>.<br>
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