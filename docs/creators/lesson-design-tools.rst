.. _lesson_design_tools_ref:

===================
Lesson design tools
===================

In this article, you will learn about:

* :ref:`develop_lesson_design_patterns_ref`
* :ref:`shortcuts_ref`
* :ref:`loopbacks_ref`
* :ref:`returning_to_earlier_cards_ref`
* :ref:`learners_choices_ref`
* :ref:`testing_and_practice_exercises_ref`
* :ref:`exploring_additional_topics_ref`
* :ref:`providing_counterexamples_ref`

.. _develop_lesson_design_patterns_ref:

Develop lesson design patterns
==============================

Once you create the basic structure of the lesson in Oppia, you can add different
branches as necessary. The following are the common design patterns you can use
for a lesson.

.. _shortcuts_ref:

Shortcuts
---------

Shortcuts allow learners who clearly understand the lesson to skip ahead. This
works well with text or open-ended questions. A typical answer would lead the
learner through the basic learning path, while a perfect answer would allow them
to skip ahead. Do this sparingly and only when an answer clearly reflects the
learner’s mastery of a topic.

.. _loopbacks_ref:

Loopbacks
---------

If a learner gives an incorrect answer, you can loop back and ask the question
again. For this process to be beneficial and educational, let the student know
what was wrong with their answer.

When using loopbacks, ensure you classify potential incorrect answers in detail
and provide feedback explaining why each answer is wrong.

Considerations and issues when using loopbacks:

* **Provide specific and constructive feedback**. Provide detailed feedback on a
  wrong answer or why the student is being redirected back to a card. The
  feedback helps the student understand the concept and find the correct answer.
* **Don't ask a different question in your feedback**. Do not provide feedback
  as a question. For example, "What if we tried it this way?" or "What about this
  number?"
* **Don't use loopbacks for incorrect text-field answers or other free-form
  classifiers**. Avoid situations where there's just one "correct" answer that
  moves the learner along but many answers that make them loop back and guess again.

.. note::
   You should use loopbacks only when you can separate the possible "wrong"
   answers into clear groups and you can give clear feedback for each incorrect
   answer group. If you cannot separate the answers into clear groups, you can
   create a new lesson branch that offers a refresher on the content.

.. _returning_to_earlier_cards_ref:

Returning to earlier cards
--------------------------

Lessons can include cycles in which learners can return to an earlier card as
they progress. This helps the student review the concept again and then answer
the question.

Avoid having the learner repeat and review many topics because of a mistake in a
single lesson. If a learner comes to an earlier card for review, make sure they
return to their original card once the review is complete. You can use shortcuts
for students who already know the answers.

.. _learners_choices_ref:

Learner’s choices
-----------------

As learners progress through their lessons, you can allow them to choose how
they want to learn the material. When creating the lesson, add branches that
will help learners make a choice:

* Sometimes, students can get confused if the question is broad or open-ended
  because they are unsure of what is expected of them. For such questions, where
  the answer could be "I don't know", add branches that will help the topic
  explain better.
* Add branches to open ended questions to catch possible misconceptions.
* If an answer triggers a misconception based on the keywords they used, be sure
  to repeat those words in the feedback to directly address the concept.

.. _testing_and_practice_exercises_ref:

Testing and practice exercises
------------------------------

Tests, exercises, and hands-on activities can utilize custom interactions. You
can branch out based on the results of an exercise:

* Did the student do what you expected?
* Are there any specific areas that the exercise revealed that need further
  attention?

While Oppia’s lessons are interactive, they can be separated into learning and
exercise sections that focus more on repetition and testing learners'
understanding.

.. _exploring_additional_topics_ref:

Exploring additional topics
---------------------------

If learners want to learn other topics, you can add diversions that lead them
down an optional branch and bring them back to the main lesson once they’ve
explored the topics.

.. _providing_counterexamples_ref:

Providing counterexamples
-------------------------

You can provide feedback for a wrong answer through counterexamples.
Counterexamples can help learners learn through discovery. Exploring potential
answers and identifying the patterns that make an answer incorrect can help
learners understand the problem and concept without relying on passive
explanations.
