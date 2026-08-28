# Lesson 12: Organizing Content with Flexbox

**Chapter:** 1 — Creating Webpages
**Duration:** 45 minutes
**Source:** [Code.org Lesson Plan](https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/12)

## Question of the Day
What are div tags and Flexbox and why are they important in web design?

## Overview
This lesson introduces students to two new web development tools: div tags and Flexbox styling. This lesson introduces students to div tags to organize their HTML code into sections. They then learn about Flexbox and how it can be used with their div containers to style and position items. Students practice using Flexbox properties to control the layout of web pages.

## Standards
CSTA K-12 Computer Science Standards (2017) — AP: Algorithms & Programming

## Objectives
Students will be able to:
- Analyze and solve common web design layout challenges using div tags and Flexbox
- Apply Flexbox properties in CSS
- Identify and explain the purpose and use of div tags in HTML

## Preparation
- Print copies of the handout.
- If you would like more information on what Flexbox is and how to use it with CSS, check out the linked video in the lesson resources.
- Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers.
- If you are teaching virtually, consider checking the Virtual Lesson Modifications.

## Vocabulary
- **Flexbox** — a layout model in CSS for displaying items
- **div** — the HTML division tag, called "div" for short, is an element that lets you group sets of content together in a container

## Introduced Code
`<div></div>`

## Levels in This Lesson
1. [Div & Flex Exploration](./Level1-DivFlexExploration/README.md) — Exploration
2. [Display, Direction and Wrap](./Level2-DisplayDirectionAndWrap/README.md) — Skill Building
3. [Justify-content](./Level3-JustifyContent/README.md) — Skill Building
4. [Align-items](./Level4-AlignItems/README.md) — Skill Building
5. [Align-content](./Level5-AlignContent/README.md) — Skill Building
6. [Practice Levels](./Level6-PracticeLevels/README.md) — Practice
7. [Wonders of the World](./Level7-WondersOfTheWorld/README.md) — Assessment
8. [Wonders of the World Reflection](./Level8-WondersOfTheWorldReflection/README.md) — Assessment
9. [Div and Flex (Challenge Levels)](./Level9-ChallengeLevels/README.md) — Challenge

## Resources

> Google Slides/Docs are linked here for reference. Actual .pptx/.pdf copies will be added to this folder separately.

**For the teachers**
- Div Containers - Resource — https://drive.google.com/file/d/1WgSOdQ-8iRA_mTUPuyJ2z9WXwszVRidH/view
- Flexbox - Resource — https://drive.google.com/file/d/18jXemehANtP7sW-Tb9Fw8ZabVFrIW5ZD/view
- Organizing My Content - Slides — https://docs.google.com/presentation/d/1jwcy6XLj_DG-uAEpgLBXF0pF0DRUIT20qfHXo_jooY4/view

**For the students**
- Flexbox Cheat Sheet - Handout — https://docs.google.com/document/d/12lL1-ZDAAb-zaM1soCdvM0OpE0OprDptcz7_rBxDtBA/view

## Teaching Guide

### Warm Up (5 minutes) — Quick Sketch
- *Remarks:* Let's warm up our design skills today with a pencil and paper. Imagine and sketch how you would design a webpage about something you love. You have complete creative freedom!
- *Prompt:* Imagine you are designing a webpage for your favorite hobby, club, pet, animal, food, or something else you love. How would you arrange the following elements: a title, a paragraph of information, and 6-8 images of the topic?
- *Do This:* Give students 2 minutes to sketch how they would like to arrange these elements quickly. Encourage creativity and personal expression. After 2 minutes, allow students to quickly share their sketches with a partner before inviting a few volunteers to share their sketches.
- *Remarks:* Now that we've seen some different ways to organize the title, text, and images, let's talk about them real quick.
- *Prompt:* Display the following discussion prompts and quickly discuss one at a time: Did you notice any common themes in how we arranged our content? What were they? What made you decide to place your title/images/text in that particular spot on the page?
- *Discussion Goal:* The discussion should reveal that organizing webpage content is a crucial part of web design. The tools they will learn today are essential for creating effective layouts, so use examples from the students' sketches to segue into the concepts of div tags and Flexbox. Mention how these tools will help them achieve the layouts they've envisioned. Students should also recognize that there is no "right" way to design a webpage.
- *Teaching Tip:* When discussing the sketches, steer the conversation towards the functionality and layout choices rather than artistic quality — this keeps the focus on web design principles. Keep the discussion concise and focused; while it's important to hear from several students, be mindful of time to ensure ample opportunity for the main activity.
- *Remarks:* Great sketches, everyone! This is a crucial part of a web developer's job which means you need the right tools to help you do this job. Today, we're going to start learning how we can bring your organization and layout ideas to life using div tags in our HTML and Flexbox in our CSS.
- Revisit the Question of the Day: What are div tags and Flexbox and why are they important in web design?

### Activity (35 minutes)

**Introduction to Div and Flex (10 minutes)**
- *Display:* Use the activity slides for this lesson to introduce students to the div tag. Use the speaker notes below as a guide. *(Look for the animation symbol on the slides indicating when animation plays when presenting — preview the slides before class.)*
- **Speaker Notes — div tags:**
  - A div tag defines a division or a section in an HTML document. It allows developers to split their webpage into distinct sections, each capable of taking on unique styles through CSS. Think of a div tag as a container for different sections of your HTML code on your page.
  - Divs go in the body section of an HTML file.
  - To create a div, you need to use an open and close tag, just as you would for a heading or paragraph tag.
  - The div tag doesn't technically do anything on its own — it can help organize an HTML file into sections, but that won't affect how those sections display on the screen. Content in a `<div>` looks the same as content not in a `<div>`.
  - Since a div element doesn't do anything on its own, you'll use the div container to group sections of code that you want to target with CSS — to style items in a div differently from other sections on the page, or to position them in a specific way. (Slides show the same HTML code in a div being displayed in two different layouts.)
- *Do This:* Use the two "Self Check" slides to gauge student understanding. Answer any questions the students may have.
- *Teaching Tip:* You can choose to either have students raise their hands to indicate which option they think is correct, or simply have them jot their letter choice down for their own reference.
- *Display:* Continue using the activity slides to introduce Flexbox.
- **Speaker Notes — Flexbox:**
  - Now that we know we can use div tags to position the code inside of it in different ways, how do we do that? Flexbox, or Flex for short, is how! Flex provides a more efficient way to lay out, align, and distribute space among items in a container.
  - The main idea behind flex is to allow the container to alter its items' width or height and even order to fill the available space best. A flex container expands the items in it to fill available free space, or shrinks them to prevent overflow.
  - Flex is the term used to refer to a whole set of CSS properties. Some are applied to the container and some are applied to the items in a container. Today we'll start with the flex properties for the div container.

**Div and Flex Practice (25 minutes)**
- *Distribute:* Pass out the Flexbox Cheat Sheet handout to the students.
- *Teaching Tip:* This handout has a section on the first page for students to write down notes to themselves. Encourage students to use this space as they go through the skill-building, practice, and challenge levels to remind themselves of anything they notice and wish to remember or refer back to later.
- *Transition:* Send students to Code Studio, Lesson 12, Level 1, and have students explore the code. Bring students' attention back to you after a few minutes of exploration.
- **Level 1 — Div & Flex Exploration:** Students explore an example page with a div container and flex properties applied.
  - *Prompt:* What did you discover about the flex properties in the CSS file?
  - *Discussion Goal:* Allow students to share what they figured out or noticed about the properties. It's okay if they didn't figure out exactly what each property does, since they will learn in the next skill-building levels. Possible discoveries: without `display: flex;` the images change position; without `flex-direction: row-reverse;` the order of the images changes; without `flex-wrap: wrap;` the images try to fit in a single row; without `justify-content: center;` the alignment of items within the container will change.
  - *Remarks:* These 4 flex properties you just played with are the ones you will use the most. When applying Flex properties to containers, you will typically follow three steps.
  - *Display:* Use the "4 Basic Flex Properties" slide to explain the 3 steps students will typically follow when applying flex properties to their containers.
  - *Teaching Tip:* This information is already in the Flexbox Cheat Sheet handout for students, but you might want to direct students to highlight, circle, or star these steps for quick reference later.
- *Group:* Group students into pairs for Pair Programming.
- *Transition:* Send students back to Code Studio and have them connect with their partner using the "Pair Programming" feature to complete the Skill Building and Practice levels.
- *Do This:* Remind students to switch driver and navigator every 3 minutes. You may want to project a digital timer at the front of the room.
- **Levels 2–5 — Skill Building:** Level 2 (Display, Direction and Wrap), Level 3 (Justify-content), Level 4 (Align-items), Level 5 (Align-content).
  - *Teaching Tip:* A slide with a timer has been provided. Delete this slide if you prefer a different method of keeping track of time for students so that they switch drivers and navigators often.
- **Level 6 — Practice Levels:** students choose from the four practice activities (not all are required).
- **Levels 7–8 — Assessment:** Level 7 (Wonders of the World) and Level 8 (a free-response reflection).
  - *Assessment Opportunity:* Levels 7 & 8 can be used as a formative assessment. Level 8 is a free response reflection that can be used as an opportunity to gain insight into how students completed the assessment level and the choices they made with using div containers and Flexbox layout. It can also be used to identify any misconceptions shared among students that should be cleared up.
- **Level 9 — Challenge Levels:** extends the lesson's skills; not required for core mastery.
  - *Teaching Tip:* It is highly advisable to have your students complete Challenge Level 9e (Image Gallery Cards) at least — the gallery product cards they will learn to build using div containers and Flexbox properties will come in very handy in the Chapter 1 project.

### Wrap Up (5 minutes) — Solving Layout and Design Issues
- *Question of the Day:* What are div tags and Flexbox and why are they important in web design?
- *Do This:* Have students include the Flexbox Reference Cheat Sheet in their notebooks if they haven't done so already.
- *Journal Prompt:* In your own words, how do div tags and Flexbox help solve page design and layout issues?
- *Discussion Goal:* Ensure students grasp the fundamental roles of div tags (structuring and grouping HTML content in a container) and Flexbox (styling and positioning elements within containers). Student responses may vary but might include design and layout issues like alignment, spacing, and organization.

---
*This work is available under a Creative Commons License (CC BY-NC-SA 4.0). For commercial licensing of CodeAI materials, contact Code.org.*
