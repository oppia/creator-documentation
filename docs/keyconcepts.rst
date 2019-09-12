.. _keyconcepts:

Key Terms used in Oppia
========================

.. admonition:: Terms

   * :ref:`Topic<topic>`
   * :ref:`Story<story>`
   * :ref:`Skill<skill>`
   * :ref:`Subtopic<subtopic>`
   * :ref:`Exploration<explorations>`
   * :ref:`Card<card>`
   * :ref:`Content<content>`
   * :ref:`Interaction<interaction>`

.. _topic:

**Topic:** A topic refers to the subject matter to be taught (e.g., Decimals, Fractions). A topic will consist of a set of stories. 

.. _story:

**Story:** Stories are non-contrived (realistic) scenarios that teach the topic. If the topic is Decimals, then the first story - aiming to introduce the concept - might be a scenario where a customer is in a shop and has to pay an amount in dollars and cents. A story consists of a set of :ref:`explorations <explorations>` or lessons.

.. note:: 
   Stories within a topic have to be linear, i.e., a student must complete a story before beginning the next story.

.. _skill:

**Skill:** A skill is simply what the student should be able to do. Following our example of Decimals, skills might include 'Comparing Decimals', 'Adding Decimals', 'Converting Decimals to Fractions' etc. Skills are normally associated with a topic.


This diagram summarizes the relationship between the above concepts:

.. figure:: /images/Topic_hierarchy.png
   :alt: Topic hierarchy
   :align: center
   
   *Topic hierarchy in Oppia*

.. _subtopic:

**Subtopic:** In Oppia, a subtopic refers to a group of skills within a topic. Subtopics are created to provide students the opportunity to review and practice skills. 

.. note:: 
   * If a skill is not assigned to a subtopic, students will not be able to practice that skill. 
   * If a subtopic is not created for a topic, students will not be able to practice the topic.

.. figure:: /images/Subtopic.png
   :alt: Subtopic hierarchy
   :align: center
   
   *Subtopics created for practicing skills*
   
.. _explorations:

**Exploration:** Explorations are lessons or learning units in Oppia. From a learner's perspective, explorations resemble a conversation between themselves and the tutor. This conversation takes the shape of: 
 
 * the tutor asking questions (content) 
 * the student answering (interaction) 
 * the student getting feedback (response)

.. _card:

**Card:** An exploration is made up of a series of cards, with each card comprised of the tutor’s question (the content) and the student’s answer (the interaction).

.. _content:

**Content:** Content refers to the *question* the tutor asks in a card. The content may include pictures, and a brief description of the context before a question is asked.

.. _interaction:

**Interaction:** Interactions refer to the *answer* that the student gives to the content (question asked), and the resulting *response* (feedback) from the tutor. The type of interaction depends on the type of exploration - a Math exploration has different interaction options from a Programming one. 

This diagram summarizes the relationship between the above concepts:

.. figure:: /images/Explorations.png
   :alt: Explorations hierarchy
   :align: center

   *Exploration hierarchy in Oppia*








