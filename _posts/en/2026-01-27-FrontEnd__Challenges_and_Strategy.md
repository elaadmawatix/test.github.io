---
ref: FrontEnd__Challenges_and_Strategy
judul: 'FrontEnd: Challenges and Strategy'
title: 'FrontEnd: Challenges and Strategy'
description: ''
tags: [idea]
category: Idea
category_url: idea
---

# FrontEnd: Challenges and Strategy

Situation:

I have a fairly complex system {[link](/en/Data_Model_part_1__Entity_DTO_Data_Transfer_Object/)}

- more than 500 tables
- FrontEnd has its own set of Challenges

At a high level, there are 2 Teams:

- Team A
    - Design - Business Process
        - Documentation files
    - Design - UI, using:
        - [figma.com](https://www.figma.com/)
        - [moqups.com](https://moqups.com/)
- Team X
    - Developer

> note: I wrote this article with the spirit of [Writing for 'Future of Me'](/en/Writing-for-Future-of-Me/)

## Strategy

To create a smooth working rhythm, I need a set of guidelines:

- define several _Big Tasks_, each with a specific goal
- CI / CD {Continuous Improvement / Continuous Development}

### FrontEnd

- HTML
    - _convert_ Design - UI to HTML
    - can be done using the tools above
    - or [Request: to AI effectively and efficiently {the right Tone}](/en/Request_to_AI_effectively_and_efficiently__the_right_Tone/)
- JavaScript
    - the part that _handles_ HTML
    - the part that _connects_ to the _end-point_ on the `BackEnd`

### BackEnd

- Part 1: Read Data
    - simple data for _Dropdown_
    - data in _Tabular_
    - using guideline as written in article [Data Model part 2 - DTO {Data Transfer Object}](/en/Data_Model_part_2__DTO_Data_Transfer_Object/)
- Part 2: CRUD
    - Simple data
    - _Header - Detail_ data
    - data with columns in `JSON format`
- Part 3:
    - the _BackEnd_ part that implements the _Design - Business Process_

> notes for BackEnd:
>
> - building each Part of the _BackEnd_ separately helps avoid getting "stuck" on the BackEnd as a whole
> - BackEnd Code can be started from the easiest part first
> - in reality, some parts of the _BackEnd_ only need "Read Data"

## For the User / Client

At the end of the day, everything is built for one purpose:
> a Product that actually works — for User/Client who use it.

That's the GOAL.<br/>
When in doubt about a decision, come back to that GOAL.<br/>
<br/>
SDR:<br/>
**S** {Situation → Specific → Simple → Speed → **Shipment**}<br/>
**D** {Define → Design → Document → Develop → **Delivery**}<br/>
**R** {Realistic → Refine → **Result**}
