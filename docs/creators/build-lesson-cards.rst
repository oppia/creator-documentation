.. _build_lesson_cards_ref:

.. _build_lesson_cards_ref:

==================
Build lesson cards
==================

In this article, you will learn how to:

* :ref:`create_lesson_card_ref`
* :ref:`add_interaction_ref`
* :ref:`add_responses_ref`
* :ref:`add_hints_ref`

.. _create_lesson_card_ref:

Create a lesson card
====================

There are four parts to a card:

1. Content
2. Interaction
3. Response
4. Loopback (optional)
5. Hint

Content
-------

The card’s content is an editable text block.

.. figure:: /images/creators/editable_text_content.png
   :alt: editable_text_content.png

   *Fig. 1. Editable text content*

Here, you can write whatever you want the learner to read. The content
should end with a question or statement that invites the learner to
interact with Oppia. You can also include rich-text elements like
images, videos and links.

Formatting Content
------------------

Oppia provides many formatting options. Let’s go through them all.

Standard text edits
~~~~~~~~~~~~~~~~~~~

Using the lettered icons **B** and *I* you can customize your text with
bold and italics.

Images, links to skills, and embedded videos
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can also insert a variety of media including:

-  Links to the skills relevant to the lesson using the chain icon
-  Images using the picture icon
-  Math expressions using the math icon

However, **avoid** using the following, which will not work on the Android app:

* Videos
* Collapsible block
* Tabs
* External links


Writing content
---------------

1. In the new card, select the white box and begin typing.
2. Set the scene.

-  Who are the characters in this story?
-  How do they connect with the lesson?
-  What situation arises that helps learners understand a new topic?

3. When you’re finished, select **Save Content**.

.. _add_interaction_ref:

Add an Interaction
==================

Interactions are the backbone of each lesson. It’s where Oppia interacts
with the learner through a question or prompting an action.

.. note::
   If you have an idea for an interaction that isn’t currently
   available, `file an issue on
   GitHub <https://github.com/oppia/oppia/issues>`__ describing this new
   interaction and what you’d like it to do. We’ll keep track of your
   request and may implement it.

Think of a question you want the learner to answer
--------------------------------------------------

What question you choose will affect what interactions are available to
best ask it to each learner.

Oppia has several built-in interactions sorted by subject matter to
choose from.

This includes:

-  Equations
-  Math expressions
-  Maps
-  Buttons
-  Menus
-  More…

.. figure:: /images/creators/interaction_types_menu.png
   :alt: interaction_types_menu.png

   *Fig. 2. Available interaction types*

Choose an interaction
~~~~~~~~~~~~~~~~~~~~~

1. Select the card you would like to add an interaction to
2. Under the Interaction panel, select **+Add interaction**
3. Select the interaction that best fits the card. This opens the
   **Customize Interaction** panel.
4. In the Customize Interaction panel, edit properties to match the
   question you are asking. For example, in a multiple choice
   interaction you can edit each option and choose the number of
   options.
5. When you’re done, select **Save Interaction.** This will take you to
   the **Responses** panel.

.. _add_responses_ref:

Add Responses
=============

After you save an interaction, the **Add Response** appears. Use
the **Add Response** panel to decide how Oppia should respond based on
the learner’s answer.

Here, you can:

-  Move the learner to a new card
-  Ask them to try again
-  Offer feedback based on their response

Even if the learner has answered correctly, explain why the answer was
right.

.. figure:: /images/creators/customized_interaction_panel.png
   :alt: customized_interaction_panel.png

   *Fig. 3. Customized interaction*

Example: Multiple choice question
---------------------------------

**Question: What is 2+3?**

I’m going to start with providing the correct answer in my multiple
choice question.

.. figure:: /images/creators/correct_answer_setup.png
   :alt: correct_answer_setup.png

   *Fig. 4. Add the correct answer: 5*

To set up a correct answer:

1. In the **If the learner’s answer…** dropdown menu, select **is equal
   to**.
2. Under the parameter menu, choose the correct option. In this case,
   it’s 5.
3. In the **Oppia tells the learner…** heading, write clear, useful
   feedback, even for correct answers.
4. Under **And afterwards, directs the learner to…, choose A new card
   called…** and enter the name of the next card\ **.**
5. Select the checkbox for **Answers in this group are correct**
6. Select **Save and Add Another**.

Add incorrect answers and responses
-----------------------------------

For each incorrect response:

1. The Rule dropdown remains **is equal to**.
2. Under Parameter, choose an incorrect answer. We’ll start with the
   response, 4.
3. Under the **Oppia tells the learner…** heading, provide specific
   feedback on why 4 is not the correct answer.
4. Under the **And afterwards, directs the learner to…** heading
   select **(try again).** This keeps the learner on the same card until
   they select the correct answer.
5. Select **Save and Add Another**.
6. Repeat for all remaining incorrect answers.

You can add, remove, and edit any response in the **Learner’s Answers
and Oppia’s Responses** panel.

Ask learners to explain their answer
------------------------------------

Once you’ve added at least one responses, the Solicit Answer Details
checkbox will appear at the bottom of the **Learner’s Answers and
Oppia’s Responses** panel. Checkmark this box to ask the learner to
explain why they chose the answer on that card.

.. figure:: /images/creators/solicit_answer_details.png
   :alt: solicit_answer_details.png

   *Fig. 5. Solicit Answer Details feature*

.. _add_hints_ref:

Add Hints
=========

Hints support learners who are struggling with a question without giving
away the full answer. You can add one or more hints to any card in your
exploration.

The **Hints** panel can be accessed at anytime towards the bottom of
the **Editor** screen. It’s grouped together with the **Learners Answers
and Oppia’s Responses** and **Interaction** panel.

When a hint appears
~~~~~~~~~~~~~~~~~~~

To ensure hints are used meaningfully, a hint can be requested only if
one of the following conditions is satisfied:

-  The learner submitted an incorrect answer at least once.
-  30 seconds have passed since the learner last submitted an answer.

How to add a hint
~~~~~~~~~~~~~~~~~

1. Select **+Add Hint** at the bottom of the **Editor** screen.
2. In the **Add Hint** panel, type out the hint
3. Select **Save Hint**.

.. figure:: /images/creators/add_hint_interface.png
   :alt: add_hint_interface.png

   *Fig. 6. Add Hint interface*
