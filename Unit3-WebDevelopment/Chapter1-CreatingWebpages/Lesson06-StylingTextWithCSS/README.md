# Lesson 6: Styling Text with CSS

**Chapter:** 1 — Creating Webpages
**Duration:** 45 minutes
**Source:** [Code.org Lesson Plan](https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/6)

## Question of the Day
How can we change the style of text on a web page?

## Overview
This lesson introduces CSS as a way to style elements on the page. Students learn the basic syntax for CSS rule-sets and then explore properties that impact HTML text elements. They work on an HTML page about Guinness World Record holders, adding their own style to the provided page. While only a few CSS properties are introduced in the core lesson, students are encouraged to use the optional activities at the end of the lesson to explore more ways that they can express themselves using CSS.

## Standards
CSTA K-12 Computer Science Standards (2017) — AP: Algorithms & Programming

## Objectives
Students will be able to:
- Explain the differences between HTML and CSS in both use and syntax.
- Link to an external style sheet.
- Use CSS selectors to style HTML text elements.

## Preparation
- Create a new poster titled "CSS Properties" if your students will not be tracking new CSS properties in their journals.
- Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers.
- If you are teaching virtually, consider checking our Virtual Lesson Modifications.

## Vocabulary
- **CSS** — Cascading Style Sheets; a language used to describe how HTML elements should be styled.
- **CSS Selector** — The part of a CSS rule-set that defines which HTML elements the style should be applied to.

## Introduced Code
`color: value;`, `font-family: value;`, `font-size: value;`, `text-align: value;`, `text-decoration: value;`

## Levels in This Lesson
1. [Sample Website](./Level1-SampleWebsite/README.md) — Exploration (Warm Up)
2. [Adding Style](./Level2-AddingStyle/README.md) — Exploration
3. [CSS and Text Color](./Level3-CSSAndTextColor/README.md) — Skill Building
4. [Making a new CSS rule-set](./Level4-MakingANewCSSRuleSet/README.md) — Skill Building
5. [Using RGB](./Level5-UsingRGB/README.md) — Skill Building
6. [Use An RGB Tool](./Level6-UseAnRGBTool/README.md) — Skill Building
7. [Changing text size](./Level7-ChangingTextSize/README.md) — Skill Building
8. [Adding a Style Sheet](./Level8-AddingAStyleSheet/README.md) — Skill Building
9. [Styling Text with CSS (Challenges)](./Level9-StylingTextWithCSSChallenges/README.md) — Practice
10. [Style this page!](./Level10-StyleThisPage/README.md) — Assessment
11. [Style the Page Reflection](./Level11-StyleThePageReflection/README.md) — Assessment
12. [Challenges and Extra Code](./Level12-ChallengesAndExtraCode/README.md) — Challenge

## Resources

> Google Slides/Docs are linked here for reference. Actual .pptx/.pdf copies will be added to this folder separately.

**For the teachers**
- Style Sheets - Resource — https://drive.google.com/file/d/1dEtUWarJQOw_iAx444hrOKZ7btSvc6VM/view
- Styling Text with CSS - Slides — https://docs.google.com/presentation/d/1oGPjHYy8Feg5pR4JRIhfz3mmo-JJjsqrUQAF0ECsHqg/view
- Text Properties - Resource — https://drive.google.com/file/d/1NoseEakxt9yOSuPbpnLgUu9-_Yso3EOB/view

**For the students**
- Intro to CSS - Part 1 - Video — https://www.youtube.com/watch?v=EP9QMdoXvXE
- Intro to CSS - Part 2 - Video — https://youtu.be/VgBVKlpLqsE

**Referenced throughout the Teaching Guide**
- Virtual Lesson Modifications — https://docs.google.com/document/d/15Gkj12vQaZmbJMZbfKk7Ec3krr1aOJeG16zy3wZ83jQ/preview
- "Teacher's Lounge" forum — https://forum.code.org/t/resource-hub-web-development-chapter-1/36190
- CSD Guide to Programming Levels — https://docs.google.com/document/d/1LlbzDHvq_DXggzeGg_sBcNov9pZX7h9NqardkGW4ELw/view
- Student Guide to Debugging — https://docs.google.com/document/d/1wNwoKDyoUas5GGkhqGmNN1u0XGQEdeOMWhSziyYIf8o/edit
- Bug Report Quarter-Sheets — https://docs.google.com/document/d/1M6mnq73DfyvzasucVAwfL-gjl2JqVPzjy_fRx5j4j7c/preview
- Google Fonts — https://fonts.google.com/
- W3Schools (CSS Fonts) — https://www.w3schools.com/css/css_font.asp

## Teaching Guide

### Warm Up (5 minutes) — Journal: HTML Appearance
- **Do This:** Send students to the sample web page in Code Studio or display it on the board (**Level 1 — Sample Website**).
- **Prompt:** Check out the web page on Code Studio. If you wanted to create a page like this, what do you already know how to do? What do you still need to learn how to do?
- **Discuss:** Have students share which parts they know and don't know.
- **Discussion Goal:** Students should notice that they can get the structure and size of the text right using headings (e.g., `<h1>`) and paragraphs `<p>`. They may notice that they cannot change the color of the text. Other styles to notice: all the paragraphs are in italics, the speech names are underlined, and the citations are much smaller than the paragraphs.
- **Remarks:** So far we have only made web pages where we control the content and structure, such as which parts of the pages are headings or paragraphs. We've been using HTML as the language to specify the content and structure of the pages. While HTML allows us some control over how the page looks, it doesn't give developers much control over the specific look and style of each element. To do that, we need a language to express style.
- **Question of the Day:** How can we change the style of text on a web page?

### Activity (30 minutes) — Web Lab: Introduction to CSS
- **Group:** Put students in pairs.
- **Transition:** Send students to Code Studio to explore **Level 2 (Adding Style — Exploration)** with their partner.
- *Teaching Tip — Guide to Programming Levels:* Additional guidance for programming levels is provided in the CSD Guide to Programming Levels, which includes strategies and best practices for facilitating programming levels with students.
- *Teaching Tip:* Have students explore Level 2 with a partner. Afterward, lead a short share out so that partners can share with the class their responses to the three questions in the instructions. The subsequent video should help reinforce what students discovered, so there's no need to lead a lengthy debrief conversation.
- **Video:** Show students the *Intro to CSS - Part 1* video in the slides and discuss the CSS video as a class. *(Teaching Tip: to encourage active engagement and reflection, use one or more of the strategies discussed in the Guide to Curriculum Videos.)*
- **Questions to Consider with the video:** How is the style of a web page different from the structure? Why might you want your web page to have a certain style?
- **Discussion Goal / Key Vocabulary:** CSS — Cascading Style Sheets, a language used to describe how HTML elements should be styled. CSS Selector — the part of a CSS rule-set that defines which HTML elements the style should be applied to.
- *Teaching Tip — Images in the Video:* Around the 40-second mark, the video briefly mentions that students have learned how to add images to their website. In a previous version of the curriculum when this video was originally recorded, students learned images before learning CSS. In the current version, students haven't seen images yet. It's a small moment in the video, but if students ask about it, use the moment to build excitement since students will be learning about images in just a few lessons!
- **Display:** Show students the slide that displays the "Content-Structure-Style" paradigm.
- **Discussion Goal:** Students should understand that the structure of the page organizes information logically but doesn't tell the computer how to display it — e.g., different headings and paragraphs say nothing about the color of text or how big it's displayed. The style of the page is the specifics of its appearance. Without a particular style, each web browser would decide how to display different web page elements on its own. Styles are important because they let web developers decide exactly how a page looks, and because styles are separate from structure and content, developers can change the style of an entire page easily without changing structure/content — giving pages a unified individual look and feel.
- **Circulate:** Support students as they continue through the first set of skill building levels — **Levels 3-7** (CSS and Text Color; Making a new CSS rule-set; Using RGB; Use An RGB Tool; Changing text size).
- *Teaching Tip — Normalizing Mistakes and Supporting Debugging:* As programming levels become more complex, students may find themselves with bugs in their code that they need to untangle. If this happens frequently, it can be demoralizing and affect self-perception. We recommend normalizing bugs and mistakes as something that happens to everyone — it's just part of the process. You can show students the Debugging Video, which includes several students normalizing mistakes and discussing debugging strategies. Consider also displaying the Student Guide to Debugging and having Bug Report Quarter-Sheets available.
- **Video:** Show students the *Intro to CSS - Part 2* video in the slides and discuss it as a class.
- **Question to Consider with Video:** How does the web page know what stylesheet it should be using?
- **Discussion Goal:** Make sure all students understand how to link to their stylesheet from each web page.
- **Circulate:** Support students as they continue through the remaining levels — **Level 8** (Adding a Style Sheet — Skill Building), **Level 9** (Practice), **Levels 10-11** (Assessment).
- *Assessment Opportunity — Formative Assessment:* Levels 10 & 11 can be used as a formative assessment. Level 11 is a free-response reflection that can be used to gain insight into how students completed the assessment level and the choices they made with CSS rule-sets and properties — it can also help identify any misconceptions shared among students that should be cleared up.
- **Level 12 — Challenges.**
- *Teaching Tip — Note on fonts and font families:* For a web browser to display a font, the font must be available on the device the browser is running on. There's no guarantee that any device has a particular font, so it's much safer to use font families, which allow for many different fonts that have the same general look and feel. If students want to specify an exact font, they'll need to use a font from the web, so the browser can download that specific font to render the page. More information on these fonts can be found at Google Fonts and W3Schools.
- **Review:** Briefly review the "Content-Structure-Style" paradigm found in the "Help and Tips" area of the Code Studio levels. Draw a T-chart on the board and label one side HTML and one side CSS. Have students work in small groups to think of as many differences as they can between the two languages, then come back together as a group and share.
- *Assessment Opportunity:* Make sure students are distinguishing between how HTML indicates the structure of a document and how CSS allows students to set the styles, as well as the differences in how the languages look on the screen and where they are used.

### Wrap Up (10 minutes) — Recording CSS Properties
- **Question of the Day:** How can we change the style of text on a web page?
- **Set Up:** Have students create a new page in their journals called "CSS Properties." *(Teaching Tip — Journal or Poster? Just as with the "HTML Tags" page in their journals, you may choose to have your class keep track of CSS Properties in a shared class poster.)*
- **Group:** Place students in groups of two to five — you'll need at least one group for each of the properties introduced in this lesson.
- **Jigsaw:** Assign each group one of the properties introduced today. Each group needs to come up with a description and example for their property.
- **Share:** Have groups add the properties they learned today to their new "CSS Properties" chart or to the class "CSS Properties" poster.
- **Key Vocabulary:** CSS — Cascading Style Sheets, a language used to describe how HTML elements should be styled; CSS Selector — the part of a CSS rule-set that defines which HTML elements the style should be applied to.

---
*This work is available under a Creative Commons License (CC BY-NC-SA 4.0). For commercial licensing of CodeAI materials, contact Code.org.*
