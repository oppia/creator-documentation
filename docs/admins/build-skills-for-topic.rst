.. _build_skills_topic_ref:

Build Skills for a Topic
========================

The success of an Oppia topic depends on how well the subject matter is decomposed into discrete, measurable units. This guide outlines how Admins and Topic Managers can effectively structure these skills.

**In this article, you will learn how to:**

* :ref:`Break down topics into skills <break_down_ref>`
* :ref:`Arrange skills logically <build_logically_ref>`
* :ref:`Group skills into subtopics <group_skills_ref>`
* :ref:`Specify prerequisite and acquired skills <skill_requirements_ref>`

---

.. _break_down_ref:

1. Break Down Topics
--------------------

The admin or topic manager should break down a Topic into as many concrete **Skills** as possible. The more Skills you generate, the easier it will be to guide learners toward a deeper understanding of a Topic.

.. tip:: **Example: Decimals Topic**

   If the Topic is decimals, generate all possible Skills related to this subject, such as:

   * Given a decimal with a zero in the one’s place, recognize that the decimal is less than one.
   * Given a decimal number, identify the whole number and fractional parts of the decimal.
   * Given a whole number, write the decimal equivalent.

.. note:: Be aware of skills that aren’t taught explicitly in the lessons but are necessary for success. For example, a learner might need to know how to estimate sums before performing specific decimal addition.

---

.. _build_logically_ref:

2. Build Logically
------------------

Arrange the Skills in an order where each one builds upon the last. A learner should be able to acquire a Skill without needing prerequisite knowledge of Skills that appear later in the sequence.

This logical flow makes it easier to plan the lesson structure. As learners progress, they build upon the knowledge and Skills previously acquired.

[Image of a learning hierarchy or skill scaffolding diagram]

---

.. _group_skills_ref:

3. Group Skills into Subtopics
------------------------------

After arranging the Skills logically, group them into **Subtopics**. This organization allows learners to review and practice specific clusters of knowledge.

**Example Grouping:**

* **Subtopic: Introduction to Decimals**
    * Given a decimal with a zero in the one’s place, recognize that the decimal is less than one.
    * Given a decimal number, identify the whole number and fractional parts of the decimal.

* **Subtopic: Decimal Concepts**
    * Given a decimal number, state the place value of each digit.
    * Given a decimal with hundredths place value, round it to the nearest tenth.

---

.. _skill_requirements_ref:

4. Specify Prerequisite Skills
------------------------------

Identify skills a learner must have that may not be part of the immediate topic scope. These should include:

* **External Skills:** Knowledge from outside the current topic.
* **Internal Skills:** Specific Skills from previous lessons in the series.

Specifying these allows Oppia to generate random review questions at the start of each lesson to ensure learners have mastered the foundations required for the current material.

5. List Acquired Skills
-----------------------

Clearly define the "Acquired Skills"—the specific abilities learners will have mastered by the end of the lesson. This list serves as the primary roadmap for lesson creators when building their explorations.
