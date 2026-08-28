# Lesson 13: Flexbox Children for More Control

**Chapter:** 1 — Creating Webpages
**Duration:** 45 minutes
**Source:** [Code.org Lesson Plan](https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/13)

## Question of the Day
How do Flexbox child properties affect the layout and organization of elements within a webpage?

## Overview
This lesson introduces students to advanced Flexbox child properties including order, align-self, flex-grow, and flex-shrink through an interactive warm-up and the various level exercises. They'll deepen their understanding of how these properties affect web page layouts and conclude with a creative group drawing game to reinforce their learning.

## Standards
CSTA K-12 Computer Science Standards (2017) — AP: Algorithms & Programming

## Objectives
Students will be able to:
- Analyze and solve common web design layout challenges using Flexbox
- Apply Flexbox children properties in CSS

## Preparation
- Print out one copy of the activity guide and handout for each student.
- Print and cut out the Pictionary Terms slips.
- If you would like more information on how to use Flexbox Children, check out the linked video in the lesson resources.
- Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers.
- If you are teaching virtually, consider checking the Virtual Lesson Modifications.

## Levels in This Lesson
1. [What Do You Notice? What Do You Wonder?](./Level1-WhatDoYouNoticeWhatDoYouWonder/README.md) — Exploration
2. [Flex-grow](./Level2-FlexGrow/README.md) — Skill Building
3. [Flex-shrink](./Level3-FlexShrink/README.md) — Skill Building
4. [Order Property](./Level4-OrderProperty/README.md) — Skill Building
5. [Align-self](./Level5-AlignSelf/README.md) — Skill Building
6. [Practice Levels](./Level6-PracticeLevels/README.md) — Practice
7. [Match The Image](./Level7-MatchTheImage/README.md) — Assessment
8. [Match the Image Reflection](./Level8-MatchTheImageReflection/README.md) — Assessment
9. [Challenge Levels](./Level9-ChallengeLevels/README.md) — Challenge

## Resources

> Google Slides/Docs are linked here for reference. Actual .pptx/.pdf copies will be added to this folder separately.

**For the teachers**
- Flexbox Children Properties - Resource — https://drive.google.com/file/d/1inb-5vkiPUldKAXpbMI4BUjuHoJZSTvL/view
- Pictionary Terms Slips - Resource — https://docs.google.com/document/d/1wNYqidP6dueDJhqukV8zyOb1PjtC9Q8lYEMvlmkl2g8/view
- Flex Children for More Control - Slides — https://docs.google.com/presentation/d/1Hoe8N9muW3MdjXbXkWB6hwBoCKd9mW6Zpu7wFd6_mJw/view

**For the students**
- Flexbox Children Cheat Sheet - Handout — https://docs.google.com/document/d/1sklhgZ-yR8AaL0XDwKMWr8gP-lLaP3QtuB8oRw2c78Q/view
- Layout Prediction - Activity Guide — https://docs.google.com/document/d/1rQl7W49mIVaCN2SQJKcdoELEv5sKnPec7kB7XPvO0UI/view

## Teaching Guide

### Warm Up (5 minutes) — Predict the Layout
- *Distribute:* Pass out the Layout Prediction Activity Guide to the students.
- *Remarks:* Let's see how well we remember what we learned last class and get a preview of some new Flex properties with a quick layout prediction game. Your challenge is to try to identify which Flex property was applied to each layout and try to predict what some new Flex properties might do! Get through as many as you can in the time provided!
- *Group:* Group students into pairs so they have someone to discuss and share their thought processes and reasoning with.
- *Do This:* Give students 3-4 minutes to work on the activity guide.
- *Do This:* Use the slides to go over the answers. Ask students for volunteer answers.
- *Teaching Tip:* As you review the answers to part 1, use this as an opportunity to ensure students clearly understand how each Flex property from the previous lesson affects the layout. Clarify students' misconceptions (such as mixing up what `justify-content` and `align-items` do, or using `justify-content` to align items horizontally when the direction is a column instead of `align-items`). The discussion should solidify their grasp of properties like `flex-direction`, `flex-wrap`, `justify-content`, and `align-content`.
- As you go over student predictions for part 2, ask students about the reasons behind their predictions. Hearing different perspectives deepens understanding and promotes a collaborative learning atmosphere, and helps students critically analyze why certain properties result in specific layout changes.
- If you have time, you can expand on what each child property does as you go over the answers to part 2.
- If any students have incorrect answers from part 1 or part 2, offer a clear explanation or analogy to help the student understand why their answer was incorrect and how the correct property works. For example: "Think of `justify-content` like when you are figuring out the spacing for posters across your bedroom wall, and `align-items` like figuring out if you want them close to your ceiling, in the center of your wall, or close to the floor," or "Think of `order` like a VIP getting to skip everyone else in line and move to the front." Reinforce that making mistakes is a natural and valuable part of the learning process. If appropriate, ask if any other students would like to add their understanding, fostering a collaborative learning atmosphere.
- *Remarks:* Well done! You're becoming quite the Flexbox detectives. Understanding these properties and predicting their effects is key to mastering web page layouts.
- Revisit the Question of the Day: How do Flexbox child properties affect the layout and organization of elements within a webpage?

### Activity (30 minutes)

**Introduction to Flex Children (5 minutes)**
- *Do This:* Use the activity slides for this lesson to introduce students to the concept of Flexbox Children. Use the speaker notes below as a guide. *(Look for the animation symbol on the slides — preview the slides before class.)*
- **Speaker Notes:**
  - After the last class, we know that we can control the layout of items, like images, by putting them inside a div container, then aligning items in a row or in columns, with control over spacing across the page, up and down the page, and whether items should wrap onto a new line or not. But what if we want even more control?
  - Our warm-up today gave you a preview of the new Flex properties we will work with today that will unleash even more power and control over our web page layouts. But these new properties won't be applied to the div container we learned about yesterday — they'll be applied to flex items inside the div container, called "children."
  - To have more control over flex items, we can target them directly with a class attribute and Flex children properties in CSS.
  - We are going to learn about four properties that can be used with Flex children: `order`, `align-self`, `flex-grow`, and `flex-shrink`. You already figured out what some of these do during our warm-up, but there is an important thing we need to know before we jump onto the computer and start building our Flex skills.
  - We have to have a container with the `display: flex` property established before any of the Flex children properties will work. Since these new properties are Flex children properties, that means the "parent" or the container tag they are nested in must have Flex established in order to see our layout change.
  - What questions do we have before we jump in and get started?

**Div and Flex Practice (25 minutes)**
- *Distribute:* Pass out the Flexbox Children Cheat Sheet handout to the students.
- *Transition:* Send students to Code Studio, Lesson 13, Level 1 and have students explore the code.
- **Level 1 — Exploration level:** Students explore an example with the new flex child properties applied.
  - *Prompt:* What did you discover about the new flex properties?
  - *Discussion Goal:* Allow students to share what they noticed about the properties. It's okay if they didn't figure out exactly what each new property does, as they will learn in the next skill-building levels. Possible discoveries: `flex-grow` seems to increase the size of an element; `flex-shrink` appears to decrease the size of an element; `order` rearranged the items. Students may also wonder why a `-1` put the item at the front while a `1` put the item at the end — this is because the default order value of all items is `0`. A negative number will put that item to the left of items with a "0" value, and an item with an order value greater than 0 will be placed to the right of items with a 0 value. (This is noted in the Cheat Sheet — encourage students to highlight or circle it.) `align-self` changes the vertical alignment for that one item.
  - *Remarks:* These 4 flex children properties you just played with are the ones you will use the most. Don't forget that when applying Flex properties to children, you need to have an established Flex layout in the container.
  - *Display:* Use the "Flex Children Steps" slide to stress establishing a Flex layout in the container before applying Flex Children properties.
- *Group:* Group students into pairs for Pair Programming.
- *Transition:* Send students back to Code Studio and have them connect with their partner using the "Pair Programming" feature to complete the Skill Building and Practice levels.
- *Do This:* Remind students to switch driver and navigator every 3 minutes. You may want to project a digital timer at the front of the room.
- **Levels 2–5 — Skill Building Levels:** Level 2 (Flex-grow), Level 3 (Flex-shrink), Level 4 (Order Property), Level 5 (Align-self).
  - *Teaching Tip:* A slide with a timer has been provided. Delete this slide if you prefer a different method of keeping track of time for students so that they switch drivers and navigators often.
- **Level 6 — Practice Levels:** students choose from the four practice activities.
- **Levels 7–8 — Assessment:** Level 7 (Match The Image) and Level 8 (a free-response reflection).
  - *Assessment Opportunity:* Levels 7 & 8 can be used as a formative assessment. Level 8 is a free response reflection that can be used as an opportunity to gain insight into how students completed the assessment level and the choices they made when adding Flexbox children properties. It can also be used to identify any misconceptions shared among students that should be cleared up.
- **Level 9 — Challenge Levels:** expand Flexbox skills with additional challenges.

### Wrap Up (10 minutes) — Flex Property Pictionary
- *Question of the Day:* How do Flexbox child properties affect the layout and organization of elements within a webpage?
- *Group:* Place students into groups of 3-4.
- *Distribute:* Pass out the Pictionary Terms slips (already cut up and in containers), blank pieces of paper, and a few markers to each group.
- *Teaching Tip:* Cut out the slips ahead of time and place them into some type of container for each group, such as a plastic cup, to save time and give students a container to pull slips from during the activity. The blank paper and markers are where students will draw their properties — if you have enough small dry-erase boards for each group, consider using those instead.
- *Optional Scoring:* If you would like this activity to have a competitive feature, instruct students that whoever guesses correctly keeps the slip of paper. At the end of the activity, students count the number of slips they have to see who guessed the most properties correctly.
- *Display:* Use the "Flex Property Pictionary" slide to help you quickly review the activity's instructions.
- *Do This:* Direct students to play the Pictionary activity until the time is up or they go through all of their slips.
- *Journal Prompt:* How did playing this game with your group help you understand Flexbox properties better?
- *Discussion Goal:* This quick reflection aims to highlight the value of collaborative learning and peer interaction — sharing ideas, discussing concepts, and working together (even by playing a game) can enhance comprehension and problem-solving skills, especially in complex subjects like web design.
- *Do This:* Have students include the Flexbox Children Cheat Sheet Reference handout in their notebooks if they haven't done so already.

---
*This work is available under a Creative Commons License (CC BY-NC-SA 4.0). For commercial licensing of CodeAI materials, contact Code.org.*
