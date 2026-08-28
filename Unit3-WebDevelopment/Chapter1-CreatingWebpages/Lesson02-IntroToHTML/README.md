# Lesson 2: Intro to HTML

**Chapter:** 1 — Creating Webpages
**Duration:** 45 minutes
**Source:** [Code.org Lesson Plan](https://studio.code.org/courses/ai-discoveries-2026/units/3/lessons/2)

## Question of the Day
How can we tell the computer both what to put on the web page, and how to organize it?

## Overview
This lesson introduces many new concepts and tools to students: HTML, the Web Lab tool, and how to navigate lesson resources on Code.org in general. Students are introduced to HTML as a solution to the problem of how to communicate both the content and structure of a website to a computer. The lesson begins with a brief unplugged activity demonstrating the challenges of effectively communicating the structure of a web page. Students then look at an exemplar HTML page in Web Lab and discuss with classmates how HTML tags help solve this problem, then write their first HTML. A wrap-up discussion solidifies the understanding of content vs. structure.

## Standards
CSTA K-12 Computer Science Standards (2017) — AP: Algorithms & Programming

## Objectives
Students will be able to:
- Explain that HTML allows a programmer to communicate the way content should be structured on a web page
- Understand how to use lesson resources provided in Web Lab
- Write a simple HTML document that uses opening and closing tags to structure content

## Preparation
- Review the Code Studio levels.
- Check the "Teacher's Lounge" forum for additional strategies/resources.
- If teaching virtually, consider the Virtual Lesson Modifications.

## Vocabulary
- **HTML** — Hypertext Markup Language, a language used to create web pages
- **HTML Element** — A piece of a website, marked by a start tag and often closed with an end tag
- **HTML Tag** — The special set of characters that indicates the start and end of an HTML element and that element's type
- **Website Content** — the text and images on a website
- **Website Structure** — how the content of a website is organized

## Introduced Code
`<!DOCTYPE>`, `<html></html>`, `<head></head>`, `<body></body>`, `<p></p>`

## Levels in This Lesson
1. [Welcome to Web Lab](./Level1-WelcomeToWebLab/README.md) — Exploration
2. [Explore HTML](./Level2-ExploreHTML/README.md) — Exploration
3. [Add Text to the Body](./Level3-AddTextToTheBody/README.md) — Skill Building
4. [Use Paragraph Tags](./Level4-UseParagraphTags/README.md) — Skill Building
5. [Debug: Broken Lines](./Level5-DebugBrokenLines/README.md) — Skill Building
6. [Practice Levels](./Level6-PracticeLevels/README.md) — Practice
7. [Fixing Dialogue](./Level7-FixingDialogue/README.md) — Assessment
8. [Fixing Dialogue Reflection](./Level8-FixingDialogueReflection/README.md) — Assessment
9. [Debug: Fix the Typos](./Level9-DebugFixTheTypos/README.md) — Challenge

## Resources

> Google Slides/Docs are linked here for reference. Actual .pptx/.pdf copies will be added to this folder separately.

**For the teachers**
- HTML Tags - Resource — https://drive.google.com/file/d/1AeYnLOk2Ugyt3Sdw0Kv7r15-oTZslFvB/view
- Exemplar Text Website - Exemplar — https://studio.code.org/projects/weblab2/UIO3vrKQ7qIsGv5boHygJrp6imx5DhGSMkdEcLgnZ4k
- Intro to HTML - Slides — https://docs.google.com/presentation/d/1zJogjm6Dx0TeVVT3NeDTUMV2xA8fNoNgyr5pBgr2_ZU/view

**For the students**
- Intro to Web Lab Part 2 - Video — https://youtu.be/Hjl6gbg9kmk
- Pair Programming - Video — https://www.youtube.com/watch?v=q7d_JtyCq1A

## Teaching Guide

### Warm Up (5 minutes) — The Need for HTML
- Display the image inside the Exemplar Text Website. *(Teaching Tip: whitelist codeprojects.org if blocked — students will publish their own pages there.)*
- **Prompt:** How could you explain to someone over the phone how to draw this web page?
- Students write instructions, then share with a neighbor.
- **Discussion Goal:** Highlight how much precision is needed to communicate instructions to a computer, and the challenge of separating content from structure — this motivates HTML.
- **Demo:** Pick a student to verbally describe the page; the teacher "draws" it literally as instructed (e.g., told to "write bigger," write the word "bigger" on the page). Have the student correct the instructions until the drawing matches, swapping students every couple of instructions, and tracking the instructions/improvements somewhere visible. Repeat until most of the page is recreated.
- Discuss the categories of information needed (location, size, font, etc.).
- **Remarks:** There's a lot of information needed to create web pages — not just content, but placement and appearance. Today we start learning the languages used on the web to represent that.
- **Key Vocabulary:** website content, website structure.

### Activity (35 minutes)

**Pair Programming**
- Group students into pairs.
- **Remarks:** We're going to explore a new tool using pair programming, which helps people write better programs together, following some rules.
- Show the Pair Programming video (in the slides). Discuss: Why do professional programmers pair program? How will it help you program better? *(Goal: promote positive attitudes — this is an industry-standard practice.)*
- Review pair programming rules: one computer; only the driver touches the keyboard/mouse; the navigator watches for problems and tracks the high-level plan; both communicate constantly; driver/navigator switch when the teacher indicates (typically every few minutes).
- *Teaching Tip:* For classes needing more collaboration support, brainstorm "sentence stems" for respectful communication ("Have you considered...", "What about...", "I think the problem might be...") before pairing up.

**Exploring HTML**
- Pairs go to Code Studio and both log in using the "Pair Programming" feature (one partner logs in, clicks their name → Pair Programming → selects partner's name → start coding as a team). Remind students to switch driver/navigator every three minutes (consider a projected timer).
- **Level 1 — Welcome to Web Lab (Exploration):** Students explore the Web Lab tool and get to know their pair-programming partner. *(Teaching Tip: use partner discussion before/after coding, then a full-group discussion on what they noticed/still wonder.)*
- Circulate; prompt: What did you notice about the workspace and preview? What other features did you discover? *(Students should notice that even multi-line text renders on one line in the preview.)*
- **Level 2 — Explore HTML (Exploration):** Students use the AI Chat tool and "Help and Tips" section. *(Note: instructions panel offers Text-to-Speech and Microsoft Immersive Reader for comprehension support.)*
- Regroup for a Think-Pair-Share on the level's discussion prompts: What code makes text bigger/bolder? What code makes text a list? What code puts text on separate lines? What code doesn't appear to do anything on screen? *(It's fine not to fully resolve these — they're covered in the next video and later in the unit. Goal: surface that HTML uses tags to surround content and indicate what it is / how it displays.)*
- Show the "Intro to Web Lab Part 2" video. Discuss: Why are HTML tags useful? What does the paragraph tag do? *(Direct answer: it separates text into paragraphs — consider asking how a screen reader might handle paragraphs differently than sighted spacing/line breaks.)*
- **Key Vocabulary:** HTML, HTML Element, HTML Tag.
- **Levels 3-5 — Skill Building** *(Level 3: Add Text to the Body; Level 4: Use Paragraph Tags; Level 5: Debug broken lines)*. *(Teaching Tip: consider Pair Programming with timed or per-level driver/navigator switches.)*
- **Level 6 — Practice** *(students choose from Creating Paragraphs / Alternating Stories / * Pyramid — not all practice levels are required)*. *(Teaching Tip: let students choose based on interest/comfort; consider having students demo their solutions to the class.)*
- **Levels 7-8 — Assessment** *(Level 7: Fixing Dialogue; Level 8: free-response reflection).* *(Assessment Opportunity: Level 8's reflection is a good window into students' choices and any shared misconceptions to clear up.)*
- **Level 9 — Challenge**, extending the lesson's skills; not required for core mastery. *(Optional video: a challenge level invites students to create poetry as a webpage, featuring poet/CS student Caia Lomeli, who was featured in the Poem Art Hour of Code — an optional inspirational tie-in to the unit's projects.)*

### Wrap Up (5 minutes) — Reflection
- **Question of the Day:** How can we tell the computer both what to put on the web page, and how to organize it?
- **Journal Prompt:** In your own words, how does HTML help solve the problem of telling a computer what a web page looks like, not just what content is on it?
- *Assessment Opportunity:* Answers should center on tags telling the computer what content "is," which in turn implies how it should look. Revisit later if needed.
- Review key vocabulary: website content, website structure, HTML, HTML Element, HTML Tag.
- **Remarks:** Content is the literal words/text; HTML provides structure by explaining how that content should be interpreted. Right now styles come from the browser's defaults — CSS (taught later in the unit) will let students style elements individually.
- Students reflect individually in their journal, then discuss with a partner, then share with the class.
- Review the board's list of lesson resources and how to use them (Level Instructions/"Do This" section; Help and Tips tab).

---
*This work is available under a Creative Commons License (CC BY-NC-SA 4.0). For commercial licensing of CodeAI materials, contact Code.org.*
