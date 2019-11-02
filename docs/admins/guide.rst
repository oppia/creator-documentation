Guide to planning a lesson
============================

This section will discuss an approach to creating engaging and effective lessons in Oppia. Whether students come to Oppia to reinforce what they learn in school, fill the gaps in their understanding, or learn something completely new—the goal for lesson creators is to consistently provide high quality lessons. Everything done within Oppia is with this goal in mind.

Before reading on, make sure you are familiar with the :ref:`key terms used in Oppia <keyconcepts>` and the relationship between them.

From a high-level perspective, the process of lesson creation looks like this:

.. figure:: /images/lesson_planning_guide.png
   :alt: Lesson Creation Process
   :align: center

   *Lesson Creation Process*


This page will elaborate on some of the steps in this process namely:

 * Creating a Skill Tree
 * Creating Questions for Skills
 * Developing a Story Outline
 * Developing a Chapter Outline

Information on the remaining steps can be found in the contents section.

.. _skilltree:

Creating a Skill Tree
----------------------

A **Skill Tree** essentially means identifying and describing the :ref:`skills <skill>` that you want the learner to master within the topic. This is the starting point for creating any lesson and is a challenging, but important step. A good way to approach this might be to look at a list of relevant questions and work backwards to identify the skills needed to answer those questions. 

.. topic:: Parts of a Skill Tree

   The following information is required to create skills:

   1. **Skill Description**:
   Skill descriptions should:

    * Be atomic, concrete and specific.
    * Describe an observable behaviour.
    * Generally use the format "Given X, compute/calculate etc. Y." For example, "Given a decimal number, state the place value of each digit."

   2. **Review Material**:
   In this section, you will give a broader explanation of the skill to help the learner understand the skill concept. This information as well as the next section 'Worked Examples' will be shown to the learner if they have trouble answering questions related to the skill.

   .. admonition:: Example
   
      If the skill is '**Identify the whole and fractional parts of a decimal**', then the review material might contain information like 'The numbers to the left of the point represent the whole number that is greater than 0, the numbers to the right represent the fractional part of the number.'

   The above two sections are mandatory to publishing a skill in Oppia. However, the following fields should be filled out as well to enhance the learning experience. 

   3. **Worked Examples**:
   Provide a list of examples that show the learner how the skill can be used to solve questions. You will be able to add images, videos, links etc. when you create this in Oppia.

   4. **Misconceptions**:
   List common mistakes and misconceptions that a learner would have when dealing with the skills. The description of misconceptions should be really specific, such that anyone should be able to read the misconception and predict how a student will answer given a question. In other words, it is insufficient to just say, "Student cannot do skill X correctly." 

   In addition, write down feedback for each misconception you identify that will be shown in the answer group for the question linked to this skill. This information will help question creators ensure that they address misconceptions and provide detailed feedback when creating questions and answer groups for the skill.

   5. **Rubrics**:
   Rubrics are useful for question creators so they have a guideline when creating questions. Rubrics can be identified for three levels of difficulty—Easy, Medium and Hard. 

   .. admonition:: Example

      For the skill '**Identify the whole and fractional parts of a decimal**', a rubric for an 'Easy' question might be:
      Given a decimal number, identify the whole number and and fractional parts of the number.
   
      A rubric for a 'Hard' question for this skill might be:
      Given a decimal number less than 1, identify the whole number and fractional parts of the number.

.. topic:: Guidelines to creating a Skill Tree

   1. **More is better.** The creator should break down a topic into as many concrete skills as possible. 

   .. admonition:: Example
      
      If the topic is Decimals, then generate all possible skills related to this topic, e.g.,
 
      * Given a decimal with a zero in the one's place, recognize that the decimal is less than one.
      * Given a decimal number, identify the whole number and fractional parts of the decimal.
      * Given a whole number, write the decimal equivalent, and so on.

   The more skills you can generate, the easier it will be to scaffold the skills and guide students towards a deeper understanding of a topic. During the review process, you will work with your reviewer to determine what skills should be included or excluded within the topic. Be aware of potential 'hidden' skills that aren't taught explicitly in the lessons.

   2. **Think logically.** Arrange the skills in such an order that they build upon one another, i.e. a learner should be able to acquire a skill without a prerequisite knowledge of skills that come after it. This will make it easier to plan the lesson structure in the next step. As students progress through lessons, they will be able to build upon knowledge and skills previously acquired.

   3. **Group skills into subtopics.** Once you have a list of skills arranged in a logical manner as described above, group the skills into subtopics. This gives students the opportunity to review and practice skills.

   .. admonition:: Example

      **Subtopic: Introduction to Decimals**
       * Given a decimal with a zero in the one's place, recognize that the decimal is less than one.
       * Given a decimal number, identify the whole number and fractional parts of the decimal.

      **Subtopic: Decimal concepts**
       * Given a decimal number, state the place value of each digit.
       * Given a decimal with hundredths place value, round it to the nearest tenths.
   
   4. **Prerequisite skills.** Specify prerequisite skills that a learner would need to have that may not be part of the topic scope. The prerequisites should also include specific skills from previous lessons in the series. These will be used to generate random review questions at the start of each lesson to determine whether the student has indeed mastered the skills they need for the present topic. 

   5. **Acquired skills.** List all the skills that learners will acquire by the end of the lesson.

Creating Questions for Skills
-------------------------------

Questions for skill practice can either be created directly by Topic Managers and Admins or suggested from contributors to Oppia. When creating questions, ensure that:

 * All misconceptions attached to the skill have been addressed in the answer groups.
 * Questions include hints and solutions.
 * Questions are varied and there is no visible pattern among them like the answer always being option 'a', for example.
 * There are more questions for harder skills.
 * Questions are as challenging and complex as they need to be if preceded by sufficient explanation.
 * At least one of the answer groups is marked as correct.
 * Questions are framed with simplicity and brevity—sticking closely with the skill being taught and not getting lost in the story details.

Developing a Story Outline
---------------------------

Usually a topic will have one story that will span across different lessons. At this stage, you will draft a high-level story for each lesson. As far as possible, try to make the content universal and free from culture or country-specific references.

Stories are what make Oppia lessons so engaging for learners. You don't have to overdo it with the story details and plot—after all, the concept being taught should be driving the lessons forward. You want just enough of a story arc to keep learners engaged and empathetic with your main character. Like any good story, there should be a challenge for your protagonist (a possible trap or misconception) that they overcome; with the learner also feeling that accomplishment by the end of the lesson.

A good way to approach this step is to think of a practical, real-world setting that best demonstrates the concept being taught, and that learners will be able to relate to. Following this, create characters that are human as opposed to animal-like to reflect a more realistic setting and ensure that you ground learners in an explanation before moving on to its application.

.. admonition:: Example

   A good real-world example for Decimals is expressing time in hours, minutes and seconds. A story emanating from this idea might be a young child who has been tasked with recording the swim time of her competing classmates using a stopwatch. This setting might span several lessons as the character learns how to read the resulting times, connect the tenths and hundredths place values to minutes and seconds, compare decimal place values and so on.

Your high-level story outline will include:

 * A brief overview of the characters, settings and premise.
 * One to two paragraphs describing what happens in each lesson.

Developing a Chapter Outline
-----------------------------

Chapter outlines will serve as a guide for lesson creators when :ref:`creating an exploration <create>` for that chapter. The outlines will 
 * inform as to what the exploration should contain,
 * ensure that explorations have a unified theme, and
 * have prerequisite and acquired skills for each lesson clearly described.