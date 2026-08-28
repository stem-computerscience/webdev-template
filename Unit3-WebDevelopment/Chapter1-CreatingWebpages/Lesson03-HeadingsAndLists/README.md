# Lesson 3: Headings and Lists

**Chapter:** 1 — Creating Webpages
**Duration:** 45 minutes
**Source:** [Code.org Lesson Plan](https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/3)

## Question of the Day
How can we work together to fix problems with our websites?

## Overview
This lesson introduces the core practices of pair programming and debugging. In this lesson, students continue to use HTML to structure text on web pages, this time in pairs, with a focus on working together and debugging problems with their sites. Students learn how to use the different heading and list elements and practice using them to give their web pages more structure.

## Standards
CSTA K-12 Computer Science Standards (2017) — AP: Algorithms & Programming

## Objectives
Students will be able to:
- Structure content into headings, subheadings, lists and paragraphs.
- Use a structured practice to collaboratively create a digital artifact.
- Use heading and list tags to change the appearance of text on a web page.

## Preparation
- Have student journals ready to give back.
- If you want to use an anchor chart, prepare poster paper to do so as a whole class.
- Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers.
- If you are teaching virtually, consider checking our Virtual Lesson Modifications.

## Vocabulary
- **Heading** — A title or summary for a document or section of a document.
- **List** — Allows web developers to group a set of related items.

## Introduced Code
`<h1></h1>`, `<li></li>`, `<ol></ol>`, `<ul></ul>`

## Levels in This Lesson
1. [Explore Heading Tags](./Level1-ExploreHeadingTags/README.md) — Exploration
2. [Headings](./Level2-Headings/README.md) — Skill Building
3. [Heading Sizes](./Level3-HeadingSizes/README.md) — Skill Building
4. [Headings Quick Check](./Level4-HeadingsQuickCheck/README.md) — Quick Check
5. [Unordered Lists](./Level5-UnorderedLists/README.md) — Skill Building
6. [Ordered Lists](./Level6-OrderedLists/README.md) — Skill Building
7. [Comments](./Level7-Comments/README.md) — Skill Building
8. [Debug: Missing Paragraph](./Level8-DebugMissingParagraph/README.md) — Practice
9. [Headings, Paragraphs, and Lists](./Level9-HeadingsParagraphsAndLists/README.md) — Assessment
10. [Headings, Paragraphs, and Lists Reflection](./Level10-HeadingsParagraphsAndListsReflection/README.md) — Assessment
11. [Extra HTML Codes](./Level11-ExtraHTMLCodes/README.md) — Challenge

## Resources

> Google Slides/Docs are linked here for reference. Actual .pptx/.pdf copies will be added to this folder separately.

**For the teachers**
- Formatting HTML - Resource — https://drive.google.com/file/d/1v2Hm5zhdWpgwYrQszmGGgqW-hEOrgPYr/view
- Headings and Paragraphs - Resource — https://drive.google.com/file/d/1Gkt6oFKQf2Upps9NuGmFAdwNgGSWDQXt/view
- Lists - Resource — https://drive.google.com/file/d/11grt8R575i98QumOvNWenMV2w9o97TwY/view
- Headings and Lists - Slides — https://docs.google.com/presentation/d/1IeGHEa2gcz_UKnXIghFm2MLlyaeOtu3i4fnmQBf7sY4/view

**For the students**
- Video: Debugging - Video — https://youtu.be/auv10y-dN4s
- Video: Pair Programming - Video — https://youtu.be/q7d_JtyCq1A

**Referenced throughout the Teaching Guide**
- CSD Guide to Programming Levels - Resource — https://docs.google.com/document/d/1LlbzDHvq_DXggzeGg_sBcNov9pZX7h9NqardkGW4ELw/view
- Student Guide to Debugging - Resource — https://docs.google.com/document/d/1wNwoKDyoUas5GGkhqGmNN1u0XGQEdeOMWhSziyYIf8o/edit
- Bug Report Quarter-Sheets - Resource — https://docs.google.com/document/d/1M6mnq73DfyvzasucVAwfL-gjl2JqVPzjy_fRx5j4j7c/preview
- Virtual Lesson Modifications — https://docs.google.com/document/d/15Gkj12vQaZmbJMZbfKk7Ec3krr1aOJeG16zy3wZ83jQ/preview
- "Teacher's Lounge" forum — https://forum.code.org/t/resource-hub-web-development-chapter-1/36190

## Teaching Guide

### Warm Up (5 minutes) — Tags Poster
- **Journal:** Have students make a three-column chart on a blank page in their journals and label the top "HTML Tags."
- *Teaching Tip — Anchor Chart / Poster:* Throughout this unit students will keep track of the tags they learn. This warm-up prompts students to record the HTML tags they learn by writing them in their journals. You can also keep track of the same information on a shared class poster or anchor chart that you update after each lesson. Prompts throughout the unit will tell you when students should update their journals, and updating the anchor chart may reinforce that process.
- **Prompt:** Yesterday, you learned about HTML, the language of the World Wide Web. HTML uses tags to structure content on web pages. Individually, think of as many tags as you remember and what they do.
- Give students a few minutes to think of as many tags as they can.
- **Remarks:** Now that you've had some time to think of your own, share your lists with a partner and see whether there's anything else you can add.
- **Discuss:** Pairs should discuss and share with one another the HTML tags they can remember and start recording their ideas on the HTML Tag Chart.
- **Discussion Goal:** Review the tags students saw in the previous lesson: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<p>`. Afterward, ask students to share the tags they came up with along with each tag's description.
- **Display:** Use the slide with the HTML Tag Chart table to help students ensure they documented all tags needed at this point, along with their descriptions:
  - `<!DOCTYPE html>` — Tells the computer that this is a document written in HTML — No closing tag
  - `<html>` — Indicates the beginning of your code written in HTML — `</html>`
  - `<head>` — Contains information (sometimes called "metadata") about your web page — `</head>`
  - `<body>` — Contains all the main content of your web page — `</body>`
  - `<p>` — Defines a paragraph — `</p>`
- As you go through the tags, highlight how working together allowed students to make their lists more comprehensive.
- *Teaching Tip:* If you choose to make a poster or anchor chart, use this time to update the chart.
- **Remarks:** Usually we are able to solve problems better when we work with someone else. That's true in programming our websites, too. Today, we're going to look at some ways that we can work together to solve different problems that our websites might have.
- **Question of the Day:** How can we work together to fix problems with our websites?

### Activity (35 minutes)
*Teaching Tip — Guide to Programming Levels:* Additional guidance for programming levels is provided in the CSD Guide to Programming Levels, which includes strategies and best practices for facilitating programming levels with students.

**Web Lab: Headings**
- **Group:** Group students into pairs.
- **Transition:** Have pairs go to Code Studio and both log in using the "Pair Programming" feature, just like yesterday.
- **Do This:** Remind students to switch driver and navigator every three minutes. Consider projecting a digital timer at the front of the room.
- **Level 1 — Explore Heading Tags (Exploration):** Circulate — give students time to explore the headings and discuss the questions on the level with their partner. **Prompt:** When would you use each of these headings? For example, which heading would you use for a web page title ... when might you use the H6 heading? *Discussion Goal:* Students should notice H1 is the largest heading tag and should therefore be used for web page titles; the remaining heading tags are used for sub-titles and section/subsection titles.
- **Levels 2-3 — Skill Building** (Level 2: Headings; Level 3: Heading Sizes).
- **Level 4 — Headings Quick Check:** A multiple choice question that asks students to choose how HTML headings will display on a web page. *Teaching Tip — Level Types:* You can see which students have answered the question correctly by going to that level and pulling out the Teacher Panel from the right-hand side. Students who have successfully answered will have a green bubble. Students have as many chances as they like to answer correctly, so guessing and checking can also lead to a correct answer. *Assessment Opportunity:* This level can be used to assess student understanding of using heading tags to change the appearance of text on a web page.
- **Transition:** Have students pause programming and bring the class back together to add heading tags to their HTML Tag Chart. **Prompt:** What are the different heading tags? Which one would we use for web page titles? What are the others for? *Discussion Goal:* Students should be able to identify six different heading tags, from `<h1>` to `<h6>`, and understand that `<h1>` is the largest, typically used for the main web page title, while the others are used for subtitles.
- **Display:** Use the slides and remarks to help students add heading tags to their HTML Tag Chart:
  - `<h1>` — Largest heading tag, typically used for web page titles — `</h1>`
  - `<h2>` to `<h6>` — Heading tags, typically used for subtitles — `</h2>` to `</h6>`
- **Remarks:** It is important to remember and record in our HTML chart that heading tags, `<h1>` through `<h6>`, are used any time we have a title or a subtitle. `<h1>` is normally used for the webpage title, while `<h2>` to `<h6>` are used for subtitles on webpages.

**Web Lab: Lists**
- **Prompt:** When might someone use a list? Think about times you have made lists. Why did you make the list? What was the list for? What type of stuff was in your list(s)? Keep track of the different types of lists students identify. *Discussion Goal:* There are many possible answers — e.g., a bulleted list for a grocery list and a numbered list for favorite movies or the steps in a recipe.
- **Display:** Show the first example of an HTML list and the result. Ask "What do you notice? What do you wonder?" *Discussion Goals — Notice:* responses may include: there are two new tags — `<ul>` and `<li>`; the result is a bulleted list; the closing `<ul>` tag comes after all the `<li>` tags; the `<li>` tags are indented. *Wonder:* what do "ul" and "li" mean? Why are there multiple `<li>` elements? Why does `<ul>` not seem to do anything? Why are the `<li>` tags indented? This prompt is purposefully open-ended, so unexpected responses are okay.
- **Do This:** Move on to the second example before answering any questions — allow the "wonder" questions to linger.
- **Display:** Show the second example of an HTML list (using `<ol>`) and the result. Again ask "What do you notice? What do you wonder?" *Discussion Goals — Notice:* the `<li>` tag is being used again; `<ol>` is used instead of `<ul>`; this time a numbered list was made; there is no content next to the starting `<ol>` tag, similar to the `<ul>` start tag in the first example (draw this observation out if no student volunteers it). *Wonder:* What does "ol" mean? Why did this example make a numbered list? Why are both examples using the `<li>` tag? Why does making a list involve two different HTML tags?
- **Discussion Goal:** Use student responses from both rounds to guide discussion, covering these key points:
  - To make an HTML list, you need both tags — the first indicating the type of list, the second indicating a list item.
  - The structure of the HTML list element is unlike other elements used so far, since there is no content that goes right next to the start `<ul>` or `<ol>` tag.
  - Indentation/whitespace in front of the `<li>` tags indicates that they are "children" nested within the list tag.
  - Once all items are listed using `<li>`, that is when the closing `</ul>` or `</ol>` tag is finally used.
  - If they want their list to have a title, they need to use one of the heading tags they just learned about.
- **Display:** Use the slide to help students add list tags to their HTML Tag Chart:
  - `<ol>` — Starts an Ordered List — `</ol>`
  - `<ul>` — Starts an Unordered List — `</ul>`
  - `<li>` — Actually creates the list item — `</li>`
- Have students continue Pair Programming through the List Skill Building levels (**Levels 5-7**: Unordered Lists, Ordered Lists, Comments).
- **Transition:** Pause programming and bring the class back together to watch the *Video: Debugging* together. Questions to consider: What is debugging? What are the four steps to debugging? *Discussion Goal:* Students should identify debugging as the process of finding and fixing problems in their code. The four steps are describing the bug, hunting for the bug, trying out small solutions (changing your code), and documenting what you have learned.
- *Teaching Tip — Normalizing Mistakes and Supporting Debugging:* As programming levels become more complex, students may run into bugs they need to untangle. If this happens frequently it can be demoralizing and affect self-perception. Normalize bugs and mistakes as something that happens to everyone — it's just part of the process. Consider displaying the Student Guide to Debugging for reference throughout the unit and having Bug Report Quarter-Sheets available for students.
- *Teaching Tip:* To encourage active engagement and reflection, use one or more of the strategies discussed in the Guide to Curriculum Videos.
- **Do This:** Have students continue Pair Programming through the remainder of the levels — **Level 8** (Practice), **Levels 9-10** (Assessment), **Level 11** (Challenge).
- *Assessment Opportunity — Formative Assessment:* Levels 9 & 10 can be used as a formative assessment. Level 10 is a free-response reflection that can be used to gain insight into how students completed the assessment level and the choices they made with the HTML tags — it can also help identify any misconceptions shared among students that should be cleared up.

### Wrap Up (5 minutes) — Journal
- **Question of the Day:** How can we work together to fix problems with our websites?
- **Key Vocabulary:** heading — a title or summary for a document or section of a document; list — allows web developers to group a set of related items.
- **Prompt:** Today, you learned a lot about debugging, which is an important skill for programmers. What is one way working with a partner helped you to debug today?
- *Assessment Opportunity:* Check that students are describing effective forms of collaboration.

---
*This work is available under a Creative Commons License (CC BY-NC-SA 4.0). For commercial licensing of CodeAI materials, contact Code.org.*
