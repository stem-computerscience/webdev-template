# Lesson 12: Organizing Content with Flexbox

Lesson 12: Organizing Content with Flexbox
45 minutes
Overview

This lesson introduces students to two new web development tools: div tags and Flexbox styling. This lesson introduces students to div tags to organize their HTML code into sections. They then learn about Flexbox and how it can be used with their div containers to style and position items. Students practice using Flexbox properties to control the layout of web pages.

Question of the Day: What are div tags and Flexbox and why are they important in web design?

Standards
Full Course Alignment
CSTA K-12 Computer Science Standards (2017)
AP - Algorithms & Programming
Agenda
Warm Up (5 minutes)
Quick Sketch
Activity (35 minutes)
Introduction to Div and Flex
Div and Flex Practice
Wrap Up (5 minutes)
Solving Layout and Design Issues
Objectives
Students will be able to:
Analyze and solve common web design layout challenges using div tags and Flexbox
Apply Flexbox properties in CSS
Identify and explain the purpose and use of div tags in HTML
Preparation
Print copies of the handout
If you would like more information on what Flexbox is and how to use it with CSS, check out this video!
Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers
If you are teaching virtually, consider checking our Virtual Lesson Modifications
Links

Heads Up! Please make a copy of any documents you plan to share with students.

For the teachers
Div Containers - Resource
Flexbox - Resource
Organizing My Content - Slides
For the students
Flexbox Cheat Sheet - Handout
Vocabulary
Flexbox - a layout model in CSS for displaying items
div - the HTML division tag, called "div" for short, is an element that lets you group sets of content together in a container
Introduced Code

<div></div>

Teaching Guide
Warm Up (5 minutes)
Quick Sketch
Remarks

Let's warm up our design skills today with a pencil and paper. I want you to imagine and sketch how you would design a webpage about something you love. You have complete creative freedom!

Prompt: Imagine you are designing a webpage for your favorite hobby, club, pet, animal, food, or something else you love. How would you arrange the following elements:

Title
Paragraph of information
6-8 images of the topic

Do This: Give students 2 minutes to sketch how they would like to arrange these elements quickly. Encourage creativity and personal expression. After 2 minutes, allow students to quickly share their sketches with a partner before inviting a few volunteers to share their sketches.

Remarks

Now that we've seen some different ways to organize the title, text, and images, let's talk about them real quick.

Prompt: Display the following discussion prompts and quickly discuss one at a time:

Did you notice any common themes in how we arranged our content? What were they?
What made you decide to place your title/images/text in that particular spot on the page?

Discussion Goal: The discussion should reveal that organizing webpage content is a crucial part of web design. The tools they will learn today are essential for creating effective layouts, so use examples from the students' sketches to segue into the concepts of div tags and Flexbox. Mention how these tools will help them achieve the layouts they've envisioned. Students should also recognize that there is no "right" way to design a webpage and that different layouts

Teaching Tip

When discussing the sketches, steer the conversation towards the functionality and layout choices rather than artistic quality. This keeps the focus on web design principles.

Keep the discussion concise and focused. While it is important to hear from several students, be mindful of the time to ensure ample opportunity for the main activity.

Remarks

Great sketches, everyone! Some great ideas for how to organize webpage content! This is a crucial part of a web developer's job which means you need the right tools to help you do this job. Today, we're going to start learning how we can bring your organization and layout ideas to life using div tags in our HTML and Flexbox in our CSS.

Question of the day: What are div tags and Flexbox and why are they important in web design?

Activity (35 minutes)
Introduction to Div and Flex (10 minutes)

Display: Use the activity slides for this lesson to introduce students to the div tag. Use the Speak Notes below as a guide to explaining what a div tag is, what it does, and why use it.

Slide notes (paraphrased):

A div tag defines a division or a section in an html document. It allows developers to split their webpage into distinct sections, each capable of taking on unique styles through CSS. Think of a div tag as a container for different sections of your html code on your page.

Divs go in the body section of an html file. To create a div, you need to use an open and close tag, just as you would for a heading or paragraph tag.

The div tag doesn't technically do anything on its own. It can help organize an HTML file into sections, but that won't affect how those sections display on the screen. Content in a <div> looks the same as content not in a <div>.

You'll use the div container to group sections of code that you want to target with CSS - to style items in a div to look different from other sections on the page, or to position them in a specific way. The same HTML code in a div can be displayed in different layouts depending on the CSS applied to the div.

Do This: Use the two "Self Check" slides to gauge student understanding. Answer any questions the students may have.

Teaching Tip

You can choose to either have students raise their hands to indicate which option they think is correct or simply have them jot their letter choice down for their own reference.

Display: Continue to use the activity slides for this lesson to introduce students to Flexbox. Use the Speaker Notes below as a guide to explaining what Flexbox is.

Slide notes (paraphrased):

Now that we know we can use div tags to position the code inside of it in different ways, the question is how do we do that? Flexbox, or Flex for short, is how! Flex provides a more efficient way to lay out, align, and distribute space among items in a container.

The main idea behind flex is to allow the container to alter its items' width or height and even order to fill the available space best. A flex container expands the items in it to fill available free space or shrinks them to prevent overflow.

Flex is the term used to refer to a whole set of CSS properties. Some are applied to the container and some are applied to the items in a container. Today, students start with the flex properties for the div container.

Div and Flex Practice (25 minutes)

Distribute: Pass out the Flexbox Cheat Sheet handout to the students.

Teaching Tip

This handout has a section on the first page for students to write down any notes to themselves. Please encourage students to use this space as they go through the skill-building, practice, and challenge levels to remind themselves of anything they notice and wish to remember or refer back to later.

Transition: Send students to Code Studio, Lesson 12, Level 1, and have students explore the code. Bring students' attention back to you after a few minutes of exploration.

Level 1 - Div & Flex Exploration

Prompt: What did you discover about the flex properties in the CSS file?

Discussion Goal: The goal of this quick discussion is to allow students to share what they figured out or what they noticed about the properties. It is okay if they didn't figure out exactly what each property does as they will learn in the next skill-building levels. Some possible discoveries might include:

Without display: flex; the images change position
Without flex-direction: row-reverse; the order of the images change
Without flex-wrap: wrap; the images try to fit in a single row
Without justify-content: center; the alignment of items within the container will change
Remarks

These 4 flex properties you just played with are the ones that you will use the most. When applying Flex properties to containers, you will typically follow three steps.

Display: Use the "4 Basic Flex Properties" slide to explain the 3 steps they will typically follow when applying flex properties to their containers.

Teaching Tip

This information is already in the Flexbox Cheat Sheet handout for students, but you might want to direct students to highlight, circle or star these steps for quick reference later.

Group: Group students into pairs for Pair Programming.

Transition: Send students back to Code Studio and have students connect with their partner using the "Pair Programming" feature to complete the Skill Building and Practice levels.

Do This: Remind students to switch driver and navigator every 3 minutes. You may want to project a digital timer at the front of the room.

Levels 2-5 - Skill Building
Teaching Tip

A slide with a timer has been provided for you. Delete this slide if you prefer a different method of keeping track of time for students so that they switch drivers and navigators often.

Level 6 - Practice Levels
Levels 7-8 - Assessment Level
Assessment Opportunity

Formative Assessment: Levels 7 & 8 can be used as a formative assessment.

Level 8 is a free response reflection that can be used as an opportunity to gain insight into how the students completed the assessment level and the choices they made with using div containers and Flexbox layout. In addition, this reflection can be used to identify any misconceptions shared among students that should be cleared up.

Level 9 - Challenge Levels
Teaching Tip

It is highly advisable to have your students complete Challenge Level 9e at least. The gallery product cards they will learn to build using div containers and Flexbox properties will come in very handy in the Chapter 1 project.

Wrap Up (5 minutes)
Solving Layout and Design Issues

Question of the Day: What are div tags and Flexbox and why are they important in web design?

Do This: Have students include the Flexbox Reference Cheat Sheet in their notebooks if they haven't done so already.

Journal Prompt: In your own words, how do div tags and Flexbox help solve page design and layout issues?

Discussion Goal: The goal of this quick reflection is to ensure students grasp the fundamental roles of div tags (structuring and grouping HTML content in a container) and Flexbox (styling and positioning elements within containers). Student responses may vary but might include design and layout issues like alignment, spacing, and organization.
