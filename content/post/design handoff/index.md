---
title: Enhanced Design Handoff with Chatbot Integration 
date: 2023-12-07
image: cover 6.jpg
description: Improving design handoffs with a Python-generated chatbot.
tags: 
    - user research
  
categories:
    - User research
    - User testing
    - Python
    - AI
    - Development

---
## Project overview

This case study is based on the paper "Code Search Role in Mitigating Divergences in Software Design: A UX Perspective", which is currently under review. The co-authors of the paper are Luca Di Grazia and Chengcheng Qu.

| Field   | Role     | Duration   |
| --------  | -------- | ------ |
| *software development* | *researcher*` | `6 months` |

## 1. Introduction

This case study outlines research conducted as part of the paper "Code Search Role in Mitigating Divergences in Software Design: A UX Perspective". The project examines how code search can improve the integration of user experience (UX) design within software development workflows, specifically during the design handoff. With advancements in AI tools like GitHub Copilot, code search has gained importance for UX practitioners and developers. Our aim was to investigate how better search tools can resolve collaboration issues and streamline the transition from design to development.

## 2. Project timeline

The research project spanned six months and was initiated within the UXO740 module of the MA in User Experience Design at Falmouth University. Key phases included:

- Initial Research (1 month): Ideation, problem definition, and hypothesis formulation.
- Data Collection (1 month): Conducting qualitative interviews with UX designers and developers, and running a quantitative survey.
- Analysis and Iteration (2 month): Identifying patterns from the data and refining our hypotheses.
- Paper Writing & Review (1 month): Preparing the findings for submission and review in an academic journal.

## 3. Methodology

We employed a mixed-methods approach:

- Qualitative: In-depth interviews with UX designers, developers, and product managers, focusing on their use of code search tools during design handoff.
- Quantitative: A survey was distributed to gather broader insights on how professionals utilize code search and where current tools fall short.
- Research Questions: Key questions included, “How does code search impact collaboration between UX designers and developers?” and “What improvements are needed to better integrate design handoff in software development?”

## 4. Findings

Our research revealed several important insights:

- Qualitative Insights: Interviewees highlighted that code search is essential for resolving ambiguities during design handoff, especially when searching for API patterns or design constraints.
- Quantitative Data: 76% of survey respondents indicated they frequently rely on free-form text queries during development. However, many noted that current search tools are not fully optimized for design-related searches.
- AI Tool Integration: Respondents expressed that tools like GitHub Copilot are transforming code search, yet improvements are needed to better accommodate UX-related queries and handoff processes.

## 5. Challenges and Lessons Learned

One of the key challenges identified in the study is the variation in code search usage across teams. While 33.3% of participants reported never using code search, the majority (77.7%) used it periodically, reflecting its essential role in the design-to-development handoff. This finding highlights that code search is crucial for both designers and developers, regardless of their background. However, current tools are not optimized for the diverse needs of both professions.

Another challenge was the complexity of integrating AI into the design handoff process. While AI tools like GitHub Copilot have shown transformative potential in retrieving context-specific code, training AI models to handle design-oriented tasks remains an area for improvement. Participants expressed the need for more designer-centric AI applications that can bridge the gap between UX design and development workflows, particularly to resolve handoff issues and reduce ambiguity.

## 6. Conclusion

The study reinforced the pivotal role of code search in facilitating collaboration between UX designers and developers during the handoff process. The research revealed a universal reliance on code search tools, with a preference for free-form text queries (86.7%), emphasizing the need for more inclusive and adaptable search interfaces. AI's role in improving code retrieval was also explored, pointing toward a future where designers could train AI to better handle design handoff tasks, thereby streamlining the process and reducing conflicts over the "source of truth."

Despite the promising insights, the study also acknowledged its limitations, such as the small sample size and potential participant bias. Future research should aim for larger, more diverse samples, focus on refining AI training models, and conduct longitudinal studies to track the long-term impact of collaborative tools on team dynamics and productivity. Further experiments on code search from a UX perspective are necessary to ensure these tools meet the unique needs of design workflows.

<!--
- themes
  - syntax

    - css
  - html
  - themes

This article offers a sample of basic Markdown syntax that can be used in Hugo content files, also it shows whether basic HTML elements are decorated with CSS in a Hugo theme.

<!--more-->

# Headings

The following HTML `<h1>`—`<h6>` elements represent six levels of section headings. `<h1>` is the highest section level while `<h6>` is the lowest.

## H1

## H2

### H3

#### H4

##### H5

###### H6

## Paragraph

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## Blockquotes

The blockquote element represents content that is quoted from another source, optionally with a citation which must be within a `footer` or `cite` element, and optionally with in-line changes such as annotations and abbreviations.

### Blockquote without attribution

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **Note** that you can use *Markdown syntax* within a blockquote.

### Blockquote with attribution

> Don't communicate by sharing memory, share memory by communicating.<br>
> — <cite>Rob Pike[^1]</cite>

[^1]: The above quote is excerpted from Rob Pike's [talk](https://www.youtube.com/watch?v=PAAkCSZUG1c) during Gopherfest, November 18, 2015.

## Tables

Tables aren't part of the core Markdown spec, but Hugo supports supports them out-of-the-box.

   Name | Age
--------|------

    Bob | 27
  Alice | 23

### Inline Markdown within tables

| Italics   | Bold     | Code   |
| --------  | -------- | ------ |
| *italics* | **bold** | `code` |

| A                                                        | B                                                                                                             | C                                                                                                                                    | D                                                 | E                                                          | F                                                                    |
|----------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------|------------------------------------------------------------|----------------------------------------------------------------------|
| Lorem ipsum dolor sit amet, consectetur adipiscing elit. | Phasellus ultricies, sapien non euismod aliquam, dui ligula tincidunt odio, at accumsan nulla sapien eget ex. | Proin eleifend dictum ipsum, non euismod ipsum pulvinar et. Vivamus sollicitudin, quam in pulvinar aliquam, metus elit pretium purus | Proin sit amet velit nec enim imperdiet vehicula. | Ut bibendum vestibulum quam, eu egestas turpis gravida nec | Sed scelerisque nec turpis vel viverra. Vivamus vitae pretium sapien |

## Code Blocks

### Code block with backticks

```html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```

### Code block indented with four spaces

    <!doctype html>
    <html lang="en">
    <head>
      <meta charset="utf-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

### Diff code block

```diff
[dependencies.bevy]
git = "https://github.com/bevyengine/bevy"
rev = "11f52b8c72fc3a568e8bb4a4cd1f3eb025ac2e13"
- features = ["dynamic"]
+ features = ["jpeg", "dynamic"]
```

### One line code block

```html
<p>A paragraph</p>
```

## List Types

### Ordered List

1. First item
2. Second item
3. Third item

### Unordered List

- List item
- Another item
- And another item

### Nested list

- Fruit
  - Apple
  - Orange
  - Banana
- Dairy
  - Milk
  - Cheese

## Other Elements — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> is a bitmap image format.

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd>CTRL</kbd> + <kbd>ALT</kbd> + <kbd>Delete</kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.
