.. _create_new_card_ref:

Create a New Card
=================

Once you have welcomed your learners with an introduction, you need to create the next step in their journey. In Oppia, this is done by linking an interaction (like a button) to a brand-new card.

**In this article, you will learn how to:**

* :ref:`Create a Continue button <create_button_interaction_ref>`
* :ref:`Link that button to a new card <link_button_new_card_ref>`

---

.. _create_button_interaction_ref:

Create a Button
---------------

This process continues from :ref:`Creating an Introduction Card <create_introduction_card_ref>`. Once your introductory content is saved:

1. Locate the **+Add Interaction** button at the bottom of the card editor.
2. Select **+Add Interaction** to open the interaction library.
3. Select the **Continue button** from the menu. This creates a simple navigation point for the learner to move forward.


---

.. _link_button_new_card_ref:

Link a Button to a New Card
---------------------------

After creating your "Continue" button, you must tell Oppia where it leads.

1. Find the **[When the button is clicked]** configuration panel.
2. Under the **Oppia tells the learner...** heading, leave the field blank (since the transition text is usually not needed for a simple "Continue" action).
3. Under the **And afterwards, directs the learner to...** dropdown menu, select **A New Card Called...**.
4. Enter a descriptive name for your new card (e.g., "Lesson Step 1") and select **Save Destination**.

   .. figure:: /images/creators/create_new_card_destination.png
      :alt: Dialog showing how to set a new card destination
      :align: center

      *Fig. 1. Directing the learner to a new card*

5. The new card will now appear in the **Exploration Overview** panel on the right side of the editor.
6. Select the card title in this panel to jump into that card and begin adding your lesson content.

   .. figure:: /images/creators/exploration_overview_panel.png
      :alt: The Exploration Overview panel showing the card hierarchy
      :align: center

      *Fig. 2. Navigation via the Exploration Overview panel*
