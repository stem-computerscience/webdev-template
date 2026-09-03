# Lesson 06: Styling Text with CSS

Lesson 6: Styling Text with CSS
45 minutes
Overview

This lesson introduces CSS as a way to style elements on the page. Students learn the basic syntax for CSS rule-sets and then explore properties that impact HTML text elements. They work on an HTML page about Guinness World Record holders, adding their own style to the provided page. While only a few CSS properties are introduced in the core lesson, students are encouraged to use the optional activities at the end of the lesson to explore more ways that they can express themselves using CSS.

Question of the Day: How can we change the style of text on a web page?

Standards
Full Course Alignment
CSTA K-12 Computer Science Standards (2017)
AP - Algorithms & Programming
Agenda
Warm Up (5 minutes)
Journal: HTML Appearance
Activity (30 minutes)
Web Lab: Introduction to CSS
Wrap Up (10 minutes)
Recording CSS Properties
Objectives
Students will be able to:
Explain the differences between HTML and CSS in both use and syntax.
Link to an external style sheet.
Use CSS selectors to style HTML text elements.
Preparation
Create a new poster titled CSS Properties if your students will not be tracking new CSS properties in their journals
Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers
If you are teaching virtually, consider checking our Virtual Lesson Modifications
Links

Heads Up! Please make a copy of any documents you plan to share with students.

For the teachers
Style Sheets - Resource
Styling Text with CSS - Slides
Text Properties - Resource
For the students
Intro to CSS - Part 1 - Video (Download)
Intro to CSS - Part 2 - Video (Download)
Vocabulary
CSS - Cascading Style Sheets; a language used to describe how HTML elements should be styled
CSS Selector - the part of a CSS rule-set that defines which HTML elements the style should be applied to
Introduced Code

color: value;

font-family: value;

font-size: value;

text-align: value;

text-decoration: value;

Teaching Guide
Warm Up (5 minutes)
Journal: HTML Appearance

Do This: Send students to the sample web page in Code Studio or display it on the board.

Level 1 - Sample Website

Prompt: Check out the web page on Code Studio. If you wanted to create a page like this, what do you already know how to do? What do you still need to learn how to do?

Discuss: Have students share which parts they know and don't know

Discussion Goal: Students should notice that they can get the structure and size of the text right using headings (e.g. <h1>) and paragraphs <p>. They may notice that they cannot change the color of the text. Some other styles to notice are that all the paragraphs are in italics, the speech names are underlined, and the citations are much smaller than the paragraphs.

Remarks

So far we have only made web pages where we control the content and structure, such as which parts of the pages are headings or paragraphs. We've been using HTML as the language to specify the content and structure of the pages. While HTML allows us some control over how the page looks, it doesn't give developers much control over the specific look and style of each element. To do that, we need a language to express style.

Question of the Day: How can we change the style of text on a web page?

Activity (30 minutes)
Web Lab: Introduction to CSS

Group: Put students in pairs.

Transition: Send students to Code Studio to explore Level 2 with their partner.

Teaching Tip

Guide to Programming Levels: Additional guidance for programming levels is provided in the CSD Guide to Programming Levels. This document includes strategies and best-practices for facilitating programming levels with students.

Level 2 - Exploration
Teaching Tip

Have students explore this level with a partner. Afterward, lead a short share out so that partners can share with the class their responses to the three questions in the instructions. The subsequent video should help reinforce what students discovered so there's no need to lead a lengthy debrief conversation.

Video: Show students the [r introtocss-part_1/ai-discoveries/2026] video in the slides and discuss the CSS video as a class.

Teaching Tip

To encourage active engagement and reflection, use one or more of the strategies discussed in the Guide to Curriculum Videos.

Questions to Consider with the video:

How is the style of a web page different from the structure?
Why might you want your web page to have a certain style?

Discussion Goal: Key Vocabulary:

CSS - Cascading Style Sheets; a language used to describe how HTML elements should be styled

CSS Selector - the part of a CSS rule-set that defines which HTML elements the style should be applied to

Teaching Tip

Images in the Video: Around the 40 second mark, the video briefly mentions that students have learned how to add images to their website. In a previous version of the curriculum when this video was originally recorded, students learned images before learning CSS. In the current version of the curriculum, students haven't seen videos yet. It's a small moment in the video, but if students ask about it, use the moment to build excitement since students will be learning about images in just a few lessons!

Display: Show students the slide that displays the "Content-Structure-Style" paradigm.

Discussion Goal: Students should understand that the structure of the page is there to organize the information in a logical way, but doesn't tell the computer how to display it. So, for example, the structure could include different headings and paragraphs but would say nothing about the color of text or how big it is displayed. The style of the page is the specifics of its appearance. Without a particular style, each web browser would decide how to display different web page elements on its own.

Styles are important to allow web developers to decide exactly how a web page looks on the screen. Because styles are separate from structure and content, web developers can change the style of an entire page very easily, without having to make any changes to the structure and content of the web page. This means that it's very easy for web pages to have an individual look and feel that is unified across the entire page.

Circulate: Support students as they continue through the first set of skill building levels.

Levels 3-7 - Skill Building
Teaching Tip

Normalizing Mistakes and Supporting Debugging: As programming levels become more complex, students may find themselves with bugs in their code that they need to untangle. If this happens frequently, this can be a demoralizing experience for students and can affect their self-perception of how capable they are in class.

To counter this, we recommend normalizing bugs and mistakes as something that happens to everyone - it's just part of the process. You can show students our Debugging Video, which includes several students normalizing mistakes and discussing debugging strategies that students can use. Additionally, consider displaying the Student Guide to Debugging for students to reference throughout the unit and having Bug Report Quarter-Sheets available for students to use.

Video: Show students the [r introtocss-part_2/ai-discoveries/2026] video in the slides and discuss it as a class.

Question to Consider with Video:

How does the web page know what stylesheet it should be using?

Discussion Goal: Make sure all the students understand how to link to their stylesheet from each web page.

Circulate: Support students as they continue through the remaining levels.

Level 8 - Skill Building
Level 9 - Practice
Levels 10-11 - Assessment
Assessment Opportunity

Formative Assessment: Levels 10 & 11 can be used as a formative assessment.

Level 11 is a free response reflection that can be used as an opportunity to gain insight into how the students completed the assessment level and the choices they made with the CSS rule sets and properties. In addition, this reflection can be used to identify any misconceptions shared among students that should be cleared up.

Level 12 - Challenges
Teaching Tip

Note on fonts and font families

For a web browser to display font, the font must be available on the device the web browser is running on. There's no guarantee that any device has a particular font, so it's much safer to use font families, which allows for many different fonts that have the same general look at feel.

If students want to specify an exact font, they'll need to use a font from the web, so the browser can download that specific font to use when rendering the page. More information on these fonts can be found at Google Fonts and W3Schools.

Review: Briefly review the "Content-Structure-Style" paradigm found in the "Help and Tips" area of the Code Studio levels. Draw a T-chart on the board and label one side HTML and one side CSS. Have students work in small groups to think of as many differences they can between the two languages, then come back together as a group and share.

Assessment Opportunity

Make sure students are distinguishing between how HTML indicates the structure of a document and how CSS allows students to set the styles, as well as the differences in how the languages look on the screen and where they are used.

Wrap Up (10 minutes)
Recording CSS Properties

Question of the Day: How can we change the style of text on a web page?

Set Up: Have students create a new page in their journals called CSS Properties.

Teaching Tip

Journal or Poster? Just as with the "HTML Tags" page in their journals, you may choose to have your class keep track of CSS Properties in a shared class poster.

Group: Place students in groups of two to five - you'll need at least one group for each of the properties introduced in this lesson.

Jigsaw: Assign each group one of the properties introduced today. Each group needs to come up with a description and example for their property.

Share: Have groups add the properties they learned today to their new "CSS Properties" chart or to the class "CSS Properties" poster.

Key Vocabulary:

CSS - Cascading Style Sheets; a language used to describe how HTML elements should be styled
CSS Selector - the part of a CSS rule-set that defines which HTML elements the style should be applied to
