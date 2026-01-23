.. _terms:

Key Terms used in Oppia
=======================

.. admonition:: Quick Links
   :class: note

   * :ref:`Story <story_ref>`
   * :ref:`Topic <topic_ref>`
   * :ref:`Subtopic <subtopic_ref>`
   * :ref:`Skill <skill_ref>`
   * :ref:`Exploration <exploration_ref>`
   * :ref:`Card <card_ref>`
   * :ref:`Content <content_ref>`
   * :ref:`Interaction <interaction_ref>`

---

.. _story_ref:

Story
-----

A story consists of a set of lessons used to teach a topic based on a
real-life example. For example, if the topic is Decimals, the story
might introduce the concept by presenting a scenario where a customer is
in a shop paying an X amount in dollars and cents.

.. _topic_ref:

Topic
-----

A topic refers to a subject a learner is learning (e.g., Decimals,
Fractions). Topics can contain both Stories (which contain a cohesive
set of lessons) and standalone lessons.

.. _subtopic_ref:

Subtopic
--------

A subtopic is a group of Skills within a Topic. Subtopics enable
learners to review and practice their Skills.

.. admonition:: Important Note
   :class: important

   * If a Skill is not assigned to a Subtopic, learners cannot practice
     that Skill.
   * If a Topic contains no Subtopics, learners won’t be able to practice
     the Topic.

.. figure:: /images/Subtopic.png
   :alt: Visual hierarchy of Topics and Subtopics
   :align: center

   *Fig. 1. Topic and subtopic hierarchy*

.. _skill_ref:

Skill
-----

Learners learn a Skill as they progress through a Topic. For example, in
the Topic decimals, students will also learn Skills like comparing
decimals, adding decimals, converting decimals to fractions, etc. Each
Skill belongs to a Topic and supports learning of that Topic.

.. figure:: /images/Topic_hierarchy.png
   :alt: Visual hierarchy of Topics and Stories
   :align: center

   *Fig. 2. Topic and Story hierarchy*

.. _exploration_ref:

Explorations
------------

Explorations (or lessons) are learning units in Oppia. Explorations are
built to resemble a conversation between the learner and a tutor. This
conversation takes the shape of:

* The tutor asks questions (**content**)
* The learner answers (**interaction**)
* The learner gets feedback (**response**)

A learner must complete the first Exploration in the Story before moving
on.

.. _card_ref:

Card
----

A lesson is made up of a series of cards, where each card consists of
the tutor’s question (the content) and the learners answer (the
interaction).

.. _content_ref:

Content
-------

Content refers to the situation and question the tutor asks on a card.
The content may include pictures and a brief context description before
a question is asked.

.. _interaction_ref:

Interaction
-----------

An interaction is the answer learners provide in response to a question
(content) and the feedback (response) from Oppia. The interaction type
depends on the lesson being taught. For example, a math lesson has
interactions that are different from a programming lesson.

.. figure:: Key%20terms/Explorations.png
   :alt: Exploration hierarchy in Oppia
   :align: center

   *Fig. 3. Exploration hierarchy in Oppia*
