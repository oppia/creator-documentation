.. _create_skill_tree_ref:

Create a Skill Tree
===================

A **Skill Tree** is the foundational blueprint for any Oppia Topic. It outlines every granular ability a learner must master. To understand how this fits into the broader ecosystem, review the :ref:`Key Terms <key_terms_ref>` and their relationships.

**In this article, you will learn how to:**

* :ref:`Build the Skill Tree structure <build_structure_ref>`
* :ref:`Improve and refine a Skill Tree <improve_tree_ref>`

---

.. _build_structure_ref:

Build the Skill Tree Structure
------------------------------

To identify the Skills needed, start with the final learning goals and **work backwards**. List out the questions a learner should be able to answer, then identify the specific skills required to solve them.

.. figure:: /images/admins/lesson_creation_process.png
   :alt: Visual of the lesson creation process
   :align: center

   *Fig. 1. Lesson creation process overview*

A Skill Tree includes:
~~~~~~~~~~~~~~~~~~~~~~

**1. Atomic Skill Descriptions**
   Descriptions must be atomic, concrete, and specific. Describe observable behavior using the format: *"Given X, compute/calculate/identify Y."*

   * *Example:* “Given a decimal number, state the place value of each digit.”

**2. Review Material**
   This explains the concept to the learner. Review material and worked examples are shown if a learner struggles with questions linked to this skill.

   .. admonition:: Technical Requirement
      :class: important

      You must publish both the **Skill Description** and **Review Materials** in Oppia for the skill to be valid.

**3. Worked Examples**
   Provide a list of step-by-step solutions showing how the skill is used. You can enrich these with images, videos, or helpful links.

**4. Misconceptions**
   Identify common mistakes learners make. For each misconception:

   * Provide a description so specific that a reviewer can predict the student's exact wrong answer.
   * Ensure feedback is drafted for each misconception to be used in the Exploration's answer groups.

**5. Rubrics**
   Guidelines for question creators to ensure consistency across difficulty levels:

   * **Easy:** Basic identification/application.
   * **Medium:** Multi-step application.
   * **Hard:** Complex application or edge cases (e.g., "Given a decimal less than 1...").

.. tip:: For more detailed guidance, see the :ref:`Skill Tree Best Practices <build_skills_topic_ref>`.

---

.. _improve_tree_ref:

Improve a Skill Tree
--------------------

**More is Better**
   Break down a topic into as many concrete skills as possible. The more granular the skills, the easier it is to pinpoint exactly where a learner is struggling. Watch out for "hidden" skills—prerequisites that aren't explicitly taught in the current lesson but are required for success.

**Think Logically**
   Arrange skills in a "building block" sequence. A learner should be able to acquire Skill A without needing knowledge of Skill B, which comes later. This logical scaffolding is essential for a smooth learning path.

**Group Skills into Subtopics**
   Once arranged, cluster your skills into subtopics (e.g., "Decimal Concepts" within an "Introduction to Decimals" topic). This allows Oppia to offer focused practice sessions.

**Specify Prerequisite vs. Acquired Skills**
   * **Prerequisite Skills:** Skills learned in previous topics or external knowledge required before starting. These trigger diagnostic "review questions" at the start of a lesson.
   * **Acquired Skills:** The specific abilities the learner will gain by the end of this specific lesson.
