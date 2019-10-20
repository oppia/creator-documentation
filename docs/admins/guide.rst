Guide to planning a lesson
============================

This section will discuss an apporach to creating engaging and effective lessons in Oppia. Whether students come to Oppia to reinforce what they learn in school, fill the gaps in their understanding, or learn something completely new—the goal for lesson creators is to consistently provide high quality lessons. Everything done within Oppia is with this goal in mind.

Before reading on, make sure you are familiar with the :ref:`key terms used in Oppia <keyconcepts>` and the relationship between them.

From a high-level perspective, the process of lesson creation looks like this:

.. figure:: /images/Lesson_creation_guide.png
   :alt: Lesson Creation Process
   :align: center

   *Lesson Creation Process*

.. _skilltree:

Creating a Skill Tree
----------------------

A **Skill Tree** essentially means identifying and describing the :ref:`skills <skill>` that you want the learner to master. This is the starting point for creating any lesson and is a challenging, but important step. A good way to approach this might be to think of complex questions and work backwards to identify the skills needed to answer those questions. A bulleted list form is absolutely fine.

Skill descriptions should:

 * Be atomic, concrete and specific.
 * Describe an observable behaviour.
 * Generally use the format "Given X, compute/calculate etc. Y." For example, "Given a decimal number, state the place value of each digit."

.. topic:: Guidelines to creating a Skill Tree

   1. **More is better.** The creator should break down a topic into as many concrete skills as possible. 

   .. admonition:: Example
      
      If the topic is Decimals, then generate all possible skills related to this topic, e.g.,
 
      * Given a decimal with a zero in the one's place, recognize that the decimal is less than one.
      * Given a decimal number, identify the whole number and fractional parts of the decimal.
      * Given a whole number, write the decimal equivalent, and so on.

   The more skills you can generate, the easier it will be to scaffold the skills and guide students towards a deeper understanding of a topic. During the review process, you will work with your reviewer to determine what skills should be included or excluded within the topic.

   2. **Think logical.** Arrange the skills in increasing order of complexity. This will make it easier to plan the lesson structure in the next step. As students progress through lessons, they will be able to build upon knowledge and skills previously acquired.

   3. **Group skills into lessons.** Once you have a list arranged from simple to complex, group the skills into lessons.

   .. admonition:: Example

      **Lesson 1: Introduction to Decimals**
       * Given a decimal with a zero in the one's place, recognize that the decimal is less than one.
       * Given a decimal number, identify the whole number and fractional parts of the decimal.

      **Lesson 2: Decimal concepts**
       * Given a decimal number, state the place value of each digit.
       * Given a decimal with hundredths place value, round it to the nearest tenths.
   
   You may choose to repeat similar skills in different lessons.


   4. **Prerequisite skills.** Specify prerequisite skills that a learner would need to have that may not be part of the topic scope. The prerequisites should also include specific skills from previous lessons in the series. These will be used to generate random review questions at the start of each lesson to determine whether the student has indeed mastered the skills they need for the present topic. 

Developing a Story Outline
---------------------------

Usually a topic will have one story that will span across different lessons. At this stage, you will draft a high-level story for each lesson.

Stories are what make Oppia lessons so engaging for learners. You don't have to overdo it with the story details and plot—after all, the concept being taught should be driving the lessons forward. You want just enough of a story arc to keep learners engaged and empathetic with your main character. Like any good story, there should be a challenge for your protagonist (a possible trap or misconception) that they overcome; with the learner also feeling that accomplishment by the end of the lesson.

A good way to approach this step is to think of a practical, real-world setting that best demonstrates the concept being taught.

.. admonition:: Example

   A good real-world example for Decimals is prices in dollars and cents. A story emanating from this idea might be a young girl in a shop grappling with a price as she tries to relate it to decimal concepts. This setting might then span several lessons as the character learns how to read the price, connects the tenths and hundredths place values to dimes and pennies, compares decimal place values and so on.

Your high-level story outline will include:

 * A brief overview of the characters, settings and premise.
 * One to two paragraphs describing what happens in each lesson.

.. _skilltable:

Creating a Skill Table
-----------------------

The Skill Table is where you will build upon the previous two steps and further elaborate the skills you have identified. Before you create the table however, list the Prerequisite skills, Acquired skills and Practiced skills for the lesson.

 * **Prerequisite skills**: Skills the learner would need before starting the lesson.
 * **Acquired skills**: Skills the learner will acquire by the end of the lesson.
 * **Practiced skills**: Skills that will be taught and practiced during the lesson.


The skill table should look like this:

.. figure:: /images/skill_table_format.png
   :alt: Skill Table format
   :align: center

   *Skill Table*


.. topic:: Explanation of columns in Skill Table

    * **Skill**: The skills you list here are the same as in the :ref:`Skill Tree <skilltree>`. Start with a target question in mind and work backwards to determine what skills students need to answer it. The more more detailed you can get while working backwards step-by-step, the more skills you will be able to identify. Be aware of potential 'hidden' skills that aren't taught explicitly in the lessons.

    * **Specific Errors**: The description of misconceptions should be really specific, such that anyone should be able to read the misconception and predict how a student will answer given a question. In other words, it is insufficient to just say, "Student cannot do skill X correctly."

    * **Remediation**: Some things you might list here include "Return to card that (addresses the misconception)." or "Show a picture that (clarifies a misunderstanding)."

    * **Development of the Topic**: This is the precursor to your script and the most important column. The questions you list here will appear in the :ref:`script <script>`. Make sure each question only introduces *one* new skill to ensure you aren't making leaps too big for the learner's understanding.
    
    Some special notations in this column include:

     - **[Concept]** tag: Denotes questions that introduce new concepts.
     - **[Test]** tag: Denotes questions that reinforce previous concepts in the lesson.
     - **[Recap]** tag: Denotes questions that reinforce previous concepts in past lessons.
     - **[Final Challenge]** tag: These are always at the *end* of the lesson and denote a series of questions that test skills taught within the lesson.
     - Colour code all types of questions with a Green, Yellow or Red highlight to denote level of difficulty.

    * **Additional Recap Questions**: The questions you list here will be added to the question bank which will allow Oppia to randomly generate equivalent questions for students—leading to a varying learning experience each time the student takes the lesson. Use the same denotations as listed in the previous column.

.. admonition:: Example
   
    * **Prerequisite Skills**: State place value of whole numbers
    * **Acquired Skills**: Identify tenths and hundredths place value in a decimal number.
    * **Practiced Skills**: State place value of decimal numbers.

   .. figure:: /images/skill_table.png
      :alt: Decimal Skill Table example
      :align: center

      *Skill Table for a lesson 'Introduction to Decimals'*

   The above example only lists the very first skill that this lesson would teach. A green highlight denotes the [CONCEPT] question as **Easy**. The table would continue to describe all the skills covered in the lesson.

.. _script:

Writing the Script
-------------------

In this stage, you will use the information from the above steps to write the script for your lesson and draft what the final product will look like in Oppia. Your script will flow from the **Development of the Topic** column of the Skill Table you created above. More specifically it will include:

 * Named cards that specify the exact dialogue, interaction type and responses.
 * Graphic requirements.  

When writing, keep the style simple and the dialogue succinct, engaging and close to the content being taught.

.. admonition:: Example
   
   **Card name**: Introduction
   
   **Content**: Chloe likes the colour purple and her favourite animal is a dog. She also loves going to the shop after school to buy candy. We're going to go with Chloe to the shop today because she is about to learn decimals (but doesn't know it yet!). 

   Before you continue, you should know 

    * what a fraction is, 
    * and can read and write fractions whole number place value.

   Ready to begin? Let's go!     

   **Interaction type**: Continue button

   **Graphic requirements**: Image of young girl

Graphics and Implementation
-----------------------------

In this final stage, you will take all the information you generated from the steps above and put it into the Oppia platform. You will write the script verbatim from the previous step.

You will also be paired with a graphics designer who will help create the graphics in your script.

.. note::

   When working with images, crop them to remove any empty space around the edges and make the alt text descriptive for users who cannot see the images. 