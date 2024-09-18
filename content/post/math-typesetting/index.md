---
title: Character Generation with Image Stabilization 
description: Building a character generator with dynamic image stabilization.
date: 2024-07-24 00:00:00+0000
image: cover 4.jpg
math: true
categories:
    - User research
    - React
    - AI
    - development
---

## Iterations

{{< youtube "NRleuAFrGPo" >}}

Stack has built-in support for math typesetting using [KaTeX](https://katex.org/).

<!--## Project overview

Bioacoustics Learn (BL) integrates online repositories to curate technical content for marine and terrestrial bioacousticians, featuring a scalable design system developed with variable parameters for enhanced usability. Community-driven user testing and research informed continuous improvement and iterations.

| Field   | Role     | Duration   |
| --------  | -------- | ------ |
| *bioacoustics* | *lead designer*` | `3 months` |

## Project Timeline

The project followed the Design Thinking methodology and the Double Diamond model, incorporating both divergent and convergent thinking. It was not linear, with overlaps and iterations occurring from the early stages.

`1 Research: 3 weeks`

`2 Define: 2 weeks`

`3 Ideate: 1 week`

`4 Prototype: 1 month`

`5 Test: 1 week`  

## Step 1: Research-->

**It's not enabled by default side-wide,** but you can enable it for individual posts by adding `math: true` to the front matter. Or you can enable it side-wide by adding `math = true` to the `params.article` section in `config.toml`.

## Inline math

This is an inline mathematical expression: $\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…$

```markdown
$\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…$
```

## Block math

$$
    \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$

```markdown
$$
    \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } 
$$
```

$$
    f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$

```markdown
$$
    f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
$$
```
