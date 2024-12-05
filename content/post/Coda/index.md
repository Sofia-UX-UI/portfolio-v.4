---
title: Coda translator 
description: Building a character generator with dynamic image stabilization.
date: 2024-07-24 00:00:00+0000
image: A4 - 9.jpg
math: true
categories:
    - User research
    - React
    - AI
    - Development
---
# Concept and Experience

Character Designer is a fine-tuned generative AI tool designed to assist users in creating detailed and high-quality personalized characters.

Our tool addresses this by streamlining the character creation process, generating both character images with image stabilization and narrative backstories through text generation based on user inputs. By fine-tuning the AI with data from trending games, Character Designer ensures the delivery of high-quality images and narratives, helping users bring their creative visions to life efficiently.

For more details, the web app can be downloaded [here](https://github.com/mrtonks/encode-ai-final-project).

## Web app Runthrough

{{< youtube "YbuVim_n6L4" >}}

## Project Overview

Character Designer is a collaborative web app developed as a final project for AI Encode Bootcamp. The team members are Jesús Vera (Front-end dev), Aleksandar Brayanov (Back-end dev), Sofía Orellano (UX/UI).

| Field   | Role     | Duration   |
| --------  | -------- | ------ |
| *Generative AI* | *ux/ui designer*` | `2 weeks` |

## Project Timeline & my contribution

As a joint project, the division of tasks mainly followed each area of expertise. My contribution covered areas of user research, market analysis, information architecture, prototyping, and user validation.

`1 User research and Planning (1 day): team communication, research`

`2 Ideation and Prototyping (4 days): ideation facilitation, user insights`

`3 Front-end dev (5 days): communication, iterations`

`4 Back-end dev (3 days): testing and user validation`

`5 Pitch Preparation (1 day): process and users feedback`

## Step 1: Initial User Research and Planning

Character Designer was the final project for the AI Bootcamp, organized by Encode Club. After several weeks of collaboration, the team developed a list of potential ideas for the final project contributed by all three members. The concept of a Character Designer was my suggestion, inspired by the potential application of generative AI, which we had been exploring during the bootcamp. It was achievable within the tight time frame, and provided a creative, unique solution.

We conducted initial user research via a [Google form](https://docs.google.com/forms/d/1gTxBcVT3Q-I7QzQCOjJTMczHnDToi5pL4X8JBRK1fOI/edit), targeting illustrators, developers, and creatives in the gaming industry. The research helped us align the project with the actual needs and pain points of users. You can view the analysis [here](https://drive.google.com/file/d/1Nl65jKSN37Ki7pXZGxMXYxzQ0wK7gc6y/view).

| Code repository   | Communication   | Design   | Cloud | Coding |
| --------  | -------- | ------ | ------ | ------ |
| *Github* | *Discord* | *Figma* | *Google Drive* | *Visual Studio Code* |

## Step 2: Ideation and Concept Development

We combined ideation, market research, and prototyping into a fast-paced, iterative process, allowing for continuous validation with team members. The main insights from user research highlighted the importance of customizable traits and backstories, as well as the need for flexible export options (e.g., PNG, JPEG, 3D models). Users also raised ethical concerns around the data used for AI-generated characters. While we couldn't address data sourcing immediately, we designed the tool to accommodate future implementation of ethical sourcing features.

{{< youtube "NRleuAFrGPo" >}}

## Step 3: Front-end dev 

A [Figma file](https://www.figma.com/design/gxO6ixJ5dPMKf3LkQXsXYf/Character-Designer?node-id=137-26145&node-type=canvas&t=Wdg3WbPEXP8VITZd-0) was shared early in the project to initiate discussions about key design elements. To accelerate development, we used Preline UI, an open-source Tailwind CSS components library, and the Material Design library for easy implementation.

The UI featured three main states: the initial dashboard, image generation, and text generation. The UI featured playful, inviting colors like:

<span style="color:#FEDADB">**Soft Peach (FEDADB)**</span>, 
<span style="color:#E4D9FF">**Lavender Mist (E4D9FF)**</span>, 
<span style="color:#DDF5DA">**Mint Green (DDF5DA)**</span> 

with familiar UI components like navigation rails, dialogs, and buttons, ensuring an intuitive and user-friendly experience.

![User flow](userflow.png)

## Step 4: Back-end dev

The back-end was integrated with the [Image Stabilization app](https://stability.ai/) and OpenAI to power the web app. While the initial plan was to run it locally, time constraints prevented full functionality from being achieved during the project timeline.

## Step 5: Pitch presentation

The pitch presentation was a key moment to showcase our project. Although we were unable to provide a live demo due to time limitations, the app successfully demonstrated its potential, with design standing out as one of the project's highlights, especially given the limited time for development.

<!--Stack has built-in support for math typesetting using [KaTeX](https://katex.org/).

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
