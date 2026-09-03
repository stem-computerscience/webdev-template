# Lesson 13: Flexbox Children for More Control

Lesson 13: Flexbox Children for More Control
45 minutes
Overview

This lesson introduces students to advanced Flexbox child properties including order, align-self, flex-grow, and flex-shrink through an interactive warm-up and the various level exercises. They'll deepen their understanding of how these properties affect web page layouts and conclude with a creative group drawing game to reinforce their learning.

Question of the Day: How do Flexbox child properties affect the layout and organization of elements within a webpage?

Standards
Full Course Alignment
CSTA K-12 Computer Science Standards (2017)
AP - Algorithms & Programming
Agenda
Warm Up (5 minutes)
Predict the Layout
Activity (30 minutes)
Introduction to Flex Children
Div and Flex Practice
Wrap Up (10 minutes)
Flex Property Pictionary
Objectives
Students will be able to:
Analyze and solve common web design layout challenges using Flexbox
Apply Flexbox children properties in CSS
Preparation
Print out one copy of the activity guide and handout for each student.
Print and cut out the Pictionary Terms slips.
If you would like more information on how to use Flexbox Children check out this video!
Check the "Teacher's Lounge" forum for verified teachers to find additional strategies or resources shared by fellow teachers
If you are teaching virtually, consider checking our Virtual Lesson Modifications
Links

Heads Up! Please make a copy of any documents you plan to share with students.

For the teachers
Flexbox Children Properties - Resource
Pictionary Terms Slips - Resource
Flex Children for More Control - Slides
For the students
Flexbox Children Cheat Sheet - Handout
Layout Prediction - Activity Guide
Teaching Guide
Warm Up (5 minutes)
Predict the Layout

Distribute: Pass out the Layout Prediction Activity Guide to the students.

Remarks

Let's see how well we remember what we learned last class and get a preview of some new Flex properties with a quick layout prediction game. Your challenge is to try to identify which Flex property was applied to each layout and try to predict what some new Flex properties might do! Get through as many as you can in the time provided!

Group: Group students into pairs so they have someone to discuss and share their thought processes and reasoning with.

Do This: Give students 3-4 minutes to work on the activity guide.

Do This: Use the slides to go over the answers. Ask students for volunteer answers.

Teaching Tip

As you review the answers to part 1, use this as an opportunity to ensure students clearly understand how each Flex property from the previous lesson affects the layout. Clarify students' misconceptions or misunderstandings (such as mixing up what justify-content and align-items do or using justify-content to align items horizontally when the direction is a column instead of align-items). The discussion should solidify their grasp of properties like flex-direction, flex-wrap, justify-content, and align-content.

As you go over student predictions for part 2, ask students about the reasons behind their predictions. Hearing different perspectives deepens understanding and promotes a collaborative learning atmosphere. This will also help foster an environment where students critically analyze why certain properties result in specific layout changes, reinforcing their knowledge and developing their problem-solving skills.

If you have time, you can expand on what each child property does as you go over the answers to part 2.

If any students have incorrect answers from part 1 or part 2, offer a clear explanation or analogy to help the student understand why their answer was incorrect and how the correct property works. For example, "Think of justify-content like when you are figuring out the spacing for posters across your bedroom wall and align-items like figuring out if you want them close to your ceiling, in the center of your wall or close to the floor" or "Think of order like a VIP getting to skip everyone else in line and move to the front." Reinforce that making mistakes is a natural and valuable part of the learning process. If appropriate, ask if any other students would like to add their understanding or explanation, fostering a collaborative learning atmosphere.

Remarks

Well done! You're becoming quite the Flexbox detectives. Understanding these properties and predicting their effects is key to mastering web page layouts.

Question of the Day: How do Flexbox child properties affect the layout and organization of elements within a webpage?

Activity (30 minutes)
Introduction to Flex Children (5 minutes)

Do This: Use the activity slides for this lesson to introduce students to the concept of Flexbox Children. Use the Speaker Notes below as a guide to explaining what Flex Children are and why you would use them.

Slide notes (paraphrased):

After the last class, we know that we can control the layout of items, like images, by putting them inside a div container, aligning items in a row or in columns, controlling spacing across the page, up and down the page, and whether items should wrap onto a new line or not. But what if we want even more control?

The warm-up gave a preview of the new Flex properties for today, which unleash even more power and control over web page layouts. But these new properties won't be applied to the div container learned about yesterday - they'll be applied to flex items inside the div container called "children". To have more control over flex items, we can target them directly with a class attribute and Flex children properties in CSS.

We are going to learn about four properties that can be used with Flex children: order, align-self, flex-grow, and flex-shrink. Students already figured out what some of these do during the warm-up, but there is an important thing to know before jumping onto the computer: we have to have a container with the display: flex property established before any of the Flex children properties will work. Since these new properties are Flex children properties, that means the "parent" or the container tag they are nested in must have Flex established in order to see the layout change.

Div and Flex Practice (25 minutes)

Distribute: Pass out the Flexbox Children Cheat Sheet handout to the students.

Transition: Send students to Code Studio, Lesson 13, Level 1 and have students explore the code.

Level 1 - Exploration level

Prompt: What did you discover about the new flex properties?

Discussion Goal: The goal of this quick discussion is to allow students to share what they noticed about the properties. It is okay if they didn't figure out exactly what each new property does, as they will learn in the next skill building levels. Some possible discoveries might include:

flex-grow seems to increase the size of an element
flex-shrink appears to decrease the size of an element
order rearranged the items
Students may also wonder why a -1 put the item at the front while a 1 put the item at the end. This is because the default order value of all items is 0. A negative number will put that to the left of items with a "0" value and an item with an order value greater than 0 will be placed to the right of items with a 0 value. This information is already noted in their Cheat Sheet but it may be helpful for students to highlight or circle the information.
align-self changes the vertical alignment for that one item
Remarks

These 4 flex children properties you just played with are the ones that you will use the most. Don't forget that when applying Flex properties to children, you need to have an established Flex layout in the container.

Display: Use the "Flex Children Steps" slide to stress establishing a Flex layout in the container before applying Flex Children properties.

Group: Group students into pairs for Pair Programming.

Transition: Send students back to Code Studio and have students connect with their partner using the "Pair Programming" feature to complete the Skill Building and Practice levels.

Do This: Remind students to switch driver and navigator every 3 minutes. You may want to project a digital timer at the front of the room.

Levels 2-5 - Skill Building Levels
Teaching Tip

A slide with a timer has been provided for you. Delete this slide if you prefer a different method of keeping track of time for students so that they switch drivers and navigators often.

Level 6 - Practice Levels
Levels 7-8 - Assessment Level
Assessment Opportunity

Formative Assessment: Levels 7 & 8 can be used as a formative assessment.

Level 8 is a free response reflection that can be used as an opportunity to gain insight into how the students completed the assessment level and the choices they made with adding Flexbox children properties. In addition, this reflection can be used to identify any misconceptions shared among students that should be cleared up.

Level 9 - Challenge Levels
Wrap Up (10 minutes)
Flex Property Pictionary

Question of the Day: How do Flexbox child properties affect the layout and organization of elements within a webpage?

Group: Place students into groups of 3-4.

Distribute: Pass out the Pictionary Terms slips already cut up and in containers, blank pieces of paper, and a few markers to each group.

Teaching Tip

You should cut out the slips ahead of time and place them into some type of container for each group, such as a plastic cup. This will save time and give the students a container to pull slips from during the activity.

The blank piece of paper and markers are where the students will be drawing their properties. If you have enough small dry-erase boards for each group, you might consider using those instead.

Optional Scoring: If you would like this activity to have a competitive feature, you can instruct students that whoever guesses correctly keeps the slip of paper. At the end of the activity, students would count the number of slips they had to see who guessed the most properties correctly.

Display: Use the "Flex Property Pictionary" slide to help you quickly review the activity's instructions.

Do This: Direct students to play the Pictionary activity until the time is up or they go through all of their slips.

Journal Prompt: How did playing this game with your group help you understand Flexbox properties better?

Discussion Goal: This quick reflection aims to highlight the value of collaborative learning and peer interaction. This reflection aims to inform students of how sharing ideas, discussing concepts, and working together (even by playing a game) can enhance their comprehension and problem-solving skills, especially in complex subjects like web design.

Do This: Have students include the Flexbox Children Cheat Sheet Reference handout in their notebooks if they haven't done so already.
