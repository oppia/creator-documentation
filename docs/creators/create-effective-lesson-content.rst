.. _create_effective_lesson_content_ref:

Create Effective Lesson Content
===============================

The goal of an Oppia lesson is to provide a personalized learning experience that feels like a 1-on-1 conversation. By anticipating learner mistakes and providing diagnostic feedback, you can guide them toward mastery without simply giving away the answers.

**In this article, you will learn:**

* :ref:`Lesson content basics <lesson_basics_ref>`
* :ref:`Example of a helpful lesson card <helpful_example_ref>`
* :ref:`Example of an unhelpful lesson card <unhelpful_example_ref>`

---

.. _lesson_basics_ref:

Lesson Content Basics
---------------------

Lessons in Oppia are called **Explorations**. These simulate a conversation between a lesson creator and a learner and are presented as a series of **cards**.

Each of these cards consists of three parts:
* **Content:** The information or a question which the learner sees.
* **Interaction:** How the learner responds (for example, multiple choice or text input).
* **Feedback:** A constructive response based on the learner's specific answer.


.. figure:: /images/creators/lesson_card_example.png
   :alt: Example of an Oppia lesson card
   :align: center

   *Fig. 1. Lesson card example*

Based on the student’s response, lesson creators can add rules to:
* Move to a harder follow-up question if they are correct.
* Ask the student to explain their answer to help identify a specific misconception.
* Teach the student how to process the question through hints or review material.

.. note::
   While the logic behind a lesson can be complex, the learner's journey always resembles a simple, linear conversation.

---

.. _helpful_example_ref:

Example of a Helpful Lesson Card
--------------------------------

Below is an example of an effective exchange. The prompts are clear, and the feedback helps the learner make progress iteratively.



**Lesson Content:** Let’s say you had a red ball, a blue ball, and a yellow ball. How many different color arrangements can you get if you put them in a straight line?

**Learner:** (thinks) There are four ways.

**Lesson Content:** OK, what are they?

**Learner:** Well, you can put the red ball on the left, the blue ball in the middle, and the yellow ball on the right – so, Red-Blue-Yellow. There’s also Blue-Red-Yellow, Blue-Yellow-Red, and Red-Blue-Yellow. That’s four ways.

**Lesson Content:** You’ve counted one of them twice…

**Learner:** Oops, oh yes. There’s an extra Red-Blue-Yellow. So, there’s three ways.

**Lesson Content:** Well, let’s check that we haven’t missed any. Let’s say the red ball is on the left. Have you found all the possibilities in that case?

**Learner:** Well, there’s Red-Blue-Yellow – oh, and Red-Yellow-Blue. Oh, and also Yellow-Blue-Red. And Yellow-Red-Blue. (Pause.) That’s all.

**Lesson Content:** OK, are you sure we haven’t missed any?

**Learner:** Well, I found all the ways with the Red ball on the left – and all the ways with the Blue ball on the left, and all the ways with the Yellow ball on the left. So that’s all.

**Lesson Content:** Yes, that’s great. It’s important to work systematically; otherwise, you’ll probably miss something. By the way, there are two arrangements for each of the three cases you mention; I’m curious why that is…?

---

.. _unhelpful_example_ref:

Example of an Unhelpful Lesson Card
-----------------------------------

Below is an example of an interaction that is **not effective**. There is no constructive feedback, there are typos, and the tone is discouraging.

**Lesson Content:** Let’s say you had a red ball, a blue ball and a yellow ball. How many different color arrangements can you get if you put them in a straight line?

**Learner:** (thinks) There are four ways.

**Lesson Content:** Wrong. Try again.

**Learner:** (thinks) There are five ways.

**Lesson Content:** Wrong. Try again

**Lesson Content:** Let’s say you had a red ball, a blue ball and a yellow ball. How many different color arrangements can you get if you put them in a straight line?

**Learner:** (thinks) There are four ways.

**Lesson Content:** No, there are six ways. This is because there are three ways to pick the ball in the first position. For each of these three ways there are two ways to pick the ball in the second position. After that, the final ball is fixed. So there are 3 x 2 x 1 ways, which is 6 ways. Do you understand?

**Learner:** …

.. tip::
   Avoid "Wrong, try again" feedback. Instead, use the learner's specific wrong answer to provide a hint that leads them back to the correct logic.
