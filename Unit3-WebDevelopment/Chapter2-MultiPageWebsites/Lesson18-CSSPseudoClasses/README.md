# Lesson 18: CSS Pseudo-classes

**Chapter:** 2 — Multi-Page Websites
**Duration:** 45 minutes
**Source:** [Code.org Lesson Plan](https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/18)

## Question of the Day
What is a CSS pseudo-class, and how does it change the way an element looks or behaves on a web page?

## Overview
This lesson introduces students to the dynamic world of CSS pseudo-classes. Students will learn about their role in enhancing web page interactivity and style. They will explore, practice, and apply various pseudo-classes like link, visited, hover, and active, understanding how these selectors can transform the user experience on websites.

## Standards
CSTA K-12 Computer Science Standards (2017) — AP: Algorithms & Programming

## Objectives
Students will be able to:
- Apply pseudo-classes to selectors in CSS to enhance website interactivity and design
- Explain the function and importance of CSS Pseudo-classes

## Preparation
- Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers.
- If you are teaching virtually, consider checking our Virtual Lesson Modifications.

## Levels in This Lesson
1. [What Do You Notice? What Do You Wonder?](./Level1-WhatDoYouNoticeWhatDoYouWonder/README.md) — Exploration
2. [Anchor Tag States - "link" & "visited"](./Level2-AnchorTagStatesLinkAndVisited/README.md) — Skill Building
3. [Anchor Tag States - "hover" & "active"](./Level3-AnchorTagStatesHoverAndActive/README.md) — Skill Building
4. [Anchor Pseudo-class Order](./Level4-AnchorPseudoClassOrder/README.md) — Skill Building
5. [Combine Pseudo-class with Classes](./Level5-CombinePseudoClassWithClasses/README.md) — Skill Building
6. [Practice Using Pseudo-classes](./Level6-PracticeUsingPseudoClasses/README.md) — Practice
7. [Adding Pseudo-classes](./Level7-AddingPseudoClasses/README.md) — Assessment
8. [Adding Pseudo-classes Reflection](./Level8-AddingPseudoClassesReflection/README.md) — Assessment
9. [Pseudo-class Challenges](./Level9-PseudoClassChallenges/README.md) — Challenge

## Resources

> Google Slides/Docs are linked here for reference. Actual .pptx/.pdf copies will be added to this folder separately.

**For the teachers**
- Pseudo-classes - Resource — https://drive.google.com/file/d/1Sguhzw0-aTJ-I09ahLb23FMfONHb046E/view
- CSS Pseudo-classes - Slides — https://docs.google.com/presentation/d/1HhQUImBgqVy0vEiYT1lswcah2SLewpwIvaYNxCAg48s/view

## Teaching Guide

### Warm Up (5 minutes) — Explore Pseudo-classes
- **Remarks:** Today, we're going to explore CSS pseudo-classes, a powerful tool that brings interactivity and style to our web pages. Let's dive in on our computers and see firsthand how these pseudo-classes can transform the look and feel of a website with just a few lines of code!
- **Transition:** Send students to Code Studio, Lesson 18, Level 1, and have students explore the code.
- **Level 1 — Exploration Level**
  - *Circulate:* As students are exploring the code, walk around to ensure students are discussing with their neighbor. Listen for and give positive affirmations to what students are noticing about the selector of the `<a>` tag. This could include the fact that there is a colon after the `<a>` selector, there are multiple selectors for the `<a>` tag, or noticing what effects different rule sets are having on the hyperlink.
  - *Prompt:* How can adding these styles impact a user's experience on a website?
  - *Discussion Goal:* This quick discussion aims to foster an understanding of how CSS pseudo-classes can enhance user experience and website usability. It aims to make students aware of the practical implications of styling links for aesthetic purposes and improving navigation, accessibility, and overall user engagement on a web page.
- **Question of the Day:** What is a CSS pseudo-class, and how does it change the way an element looks or behaves on a web page?

### Activity (35 minutes) — Pseudo-class Practice
- **Remarks:** Before you continue on to the rest of the levels, there's one very important thing you need to know when using pseudo-classes with links — the order matters! You will see this in your first Skill Building level but let's go over it real quick.
- **Display:** Use the "Link Pseudo-classes" slides to explain the order in which those pseudo-classes must be applied for anchor tags.
- *Teaching Tip:* All of these pseudo-classes can apply to a hyperlink; in some cases, more than one will apply. For example, an unvisited link can be hovered and active simultaneously as it's an unvisited link. Since these four rules apply to the hyperlink, and the selectors all have the same specificity, then the last one listed that matches what the user is doing, wins.
- If we mix up the order, for example, this means that if "hover" was after "active," the "active" style will never appear because the "hover" style will always override it. For this reason, the recommended order is:
  ```
  a:link
  a:visited
  a:hover
  a:active
  ```
- Here's a fun way for students to remember the order — Just have them remember LOVE (LV) & HATE (HA).
- **Group:** Group students into pairs for Pair Programming.
- **Transition:** Send students back to Code Studio and have students connect with their partner using the "Pair Programming" feature to complete the Skill Building and Practice levels.
- **Do This:** Remind students to switch driver and navigator every 3 minutes. You may want to project a digital timer at the front of the room.
- **Levels 2-5 — Skill Building Levels**
  - *Teaching Tip:* A slide with a timer has been provided for you. Delete this slide if you prefer a different method of keeping track of time for students so that they switch drivers and navigators often.
- **Level 6 — Practice Levels**
- **Levels 7-8 — Assessment Level**
  - *Formative Assessment:* Levels 7 & 8 can be used as a formative assessment.
  - Level 8 is a free response reflection that can be used as an opportunity to gain insight into how the students completed the assessment level and the choices they made with adding and styling pseudo-classes. In addition, this reflection can be used to identify any misconceptions shared among students that should be cleared up.
- **Level 9 — Challenge Levels**

### Wrap Up (5 minutes)
- **Question of the Day:** What is a CSS pseudo-class, and how does it change the way an element looks or behaves on a web page?
- **Do This:** Have students update their CSS Charts in their journals to include the pseudo-classes.
- **Prompt:** How might you use pseudo-classes in your group's project to enhance the aesthetics and functionality of your website?
- **Discussion Goal:** This quick reflection encourages students to think about the practical application of the concepts they've learned. By considering how to incorporate pseudo-classes into their projects, students move from theoretical understanding to practical usage, which is crucial for deep learning and skill retention. It also considers how different pseudo-classes can enhance the aesthetics and functionality of their project, leading to a more engaging and user-friendly end product.

---
*This work is available under a Creative Commons License (CC BY-NC-SA 4.0). For commercial licensing of CodeAI materials, contact Code.org.*
