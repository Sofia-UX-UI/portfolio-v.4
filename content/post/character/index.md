---
title: Character Generation with Image Stabilization 
description: Building a character generator with dynamic image stabilization.
date: 2024-07-24 00:00:00+0000
image: cover 4.jpg
math: true
categories:
    - User research
    - React
    - Generative AI
    - Development
---
# Concept and Experience

Character Designer is a fine-tuned generative AI tool designed to assist users in creating detailed and high-quality personalized characters.

Our tool addresses this by streamlining the character creation process, generating both character images with image stabilization and narrative backstories through text generation based on user inputs. By fine-tuning the AI with data from trending games, Character Designer ensures the delivery of high-quality images and narratives, helping users bring their creative visions to life efficiently.

For more details, the PC version of the game can be downloaded [here](https://foxracinggurl.itch.io/nomads-notes).

## Web app Runthrough

{{< youtube "YbuVim_n6L4" >}}

## Project Overview

Character Designer is a collaborative web app developed as a final project for AI Encode Bootcamp. The team members are Jesús Vera (Front-end dev), Aleksandar Brayanov (Back-end dev), Sofía Orellano (UX/UI).

| Field   | Role     | Duration   |
| --------  | -------- | ------ |
| *Generative AI* | *ux/ui designer*` | `12 weeks` |

<!--## Project Timeline & my contribution

As a collaborative project, the division of tasks mainly followed each area of expertise. My contribution covered areas of user research, academic research, market analysis, information architecture, user validation, and user testing.

`1 Initial Research and Planning (2 weeks): team coordination, project setup, communication management`

`2 Ideation and Concept Development (2 weeks): ideation facilitation, concept refinement`

`3 Research (2 weeks): academic research, user insights`

`4 Define (2 weeks): mapping and market analysis`

`5 Game Design & Mechanics (8 weeks): information Architecture, prototypying & interaction`

`4 Pitch Preparation (2 weeks): market focus`

`5 User Testing & Feedback (1 week): creation and data analysis`  

## Iterations

{{< youtube "NRleuAFrGPo" >}}

Stack has built-in support for math typesetting using [KaTeX](https://katex.org/).

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
