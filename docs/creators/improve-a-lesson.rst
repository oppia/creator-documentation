.. _improve_a_lesson_ref:

================
Improve a lesson
================

In this article, you will learn how to:

* :ref:`view_lesson_statistics_ref`
* :ref:`review_feedback_on_a_card_ref`
* :ref:`add_branches_to_a_lesson_ref`

.. _view_lesson_statistics_ref:

View lesson statistics
======================

In the Creator Dashboard, below each lesson you'll see:

* Average rating (star icon)
* Views (eye icon)
* Open feedback (message icon)
* Last updated (clock icon)

.. figure:: /images/creators/creator_dashboard_stats.png
   :alt: The Creator Dashboard showing individual lesson cards with icons for ratings, views, and feedback.

   *Fig. 1. Lessons a lesson creator has made*

.. _view_detailed_lesson_statistics_ref:

To view detailed lesson statistics:

1. In the **Exploration Editor**, select **Statistics** (the graph icon) in the 
   navigation menu to see how many learners have completed the lesson and the 
   path they took to finish it.

.. figure:: /images/creators/exploration_completion_stats.png
   :alt: The Statistics tab in the Exploration Editor showing a completion rate graph and learner path data.

   *Fig. 2. Exploration completion rates*

The **Exploration Stats** panel shows how often each card was completed, each 
rule for a given card was triggered, and the different answers learners 
submitted.

* For example, if a particular wrong answer was submitted for a card, you could 
  use this information to include a new rule, content, or branch to help 
  learners move through the lesson easier.
* To edit a card, select the card name under **Common learner paths**.

You can sort the explorations and select **Open Feedback** to view explorations 
with feedback.

Exit rate statistics
--------------------

Oppia also provides statistics on where the learner quit in a lesson. 

.. figure:: /images/creators/statistics_exit_rates.png
   :alt: A bar chart within the Statistics screen showing the number of learners who exited the lesson at specific cards.

   *Fig. 3. Statistics showing how many left before completing a lesson*

1. To see statistics on the exit rate, open the **Statistics** panel and select
   the card. A pop up appears with details about how many learners exited on
   that card. 

.. figure:: /images/creators/card_exit_details.png
   :alt: A detailed pop-up for a specific card showing the percentage of learners who dropped off at that point.

   *Fig. 4. Statistics shown for each card*

.. note::
   Be aware of patterns here. If learners quit a particular card, the 
   difficulty level may be too high, or the content may be ambiguous. 

.. _review_feedback_on_a_card_ref:

Review feedback on a card
=========================

Learners can provide feedback on each card as they go through a lesson. 

1. In the **Exploration Editor**, select **Feedback** (message icon). You 
   will see the open feedback for the Exploration. 

.. figure:: /images/creators/lesson_feedback_list.png
   :alt: The Feedback tab showing a list of threads submitted by learners for specific cards in the exploration.

   *Fig. 5. Lesson feedback for each card*

2. Select **Open** to respond to the feedback. 
3. Respond to the feedback and select **Send**. If you’re still working on the 
   task, leave the status open. You can also change the status based on your 
   response.

.. figure:: /images/creators/feedback_thread_response.png
   :alt: An open feedback thread with a text area for responding to the learner and a dropdown to change the status.

   *Fig. 6. Feedback threads to address and respond to learner feedback*

.. _add_branches_to_a_lesson_ref:

Add branches to a lesson
========================

When building a lesson, create a single series of questions and answers that 
help learners understand the concept. This is the *trunk* of your lesson. You 
can add branches to this trunk as learners engage with your lesson and you 
notice patterns in their responses.

.. figure:: /images/creators/branched_lesson_overview.png
   :alt: A flow diagram in the Exploration Overview showing a main path with a side branch for addressing misconceptions.

   *Fig. 7. Example of a branched lesson*

For example, if learners are answering "Hundreds" to a decimal place-value
question, this might indicate that they are mistakenly equating the place
values of decimals with those of whole numbers. You can branch out from this
card and provide further explanation to correct this misconception.

1. In **Exploration Editor**, select the card in question, and under 
   **Learner’s Answers and Oppia’s responses**, select the incorrect answer 
   option.
2. Select **A New Card Called…** from the drop-down menu to add a card that 
   branches out from the incorrect answer.
3. Add a title to the card and select **Save Destination**. The new card is now 
   visible in the **Exploration Overview** section.

.. figure:: /images/creators/branch_misconception_setup.png
   :alt: Setting a response destination to a new card to address a specific misconception.

   *Fig. 8. Direct the learner to address a misconception*

4. Open the card to add content. You can add several cards on this branch and 
   redirect the learner back to a card on the main path of the exploration.

.. figure:: /images/creators/lesson_branch_nodes.png
   :alt: The exploration overview map showing new card nodes being added to a side branch.

   *Fig. 9. Lesson branch*

.. figure:: /images/creators/completed_branch_path.png
   :alt: The final overview map showing a side branch rejoining the main lesson trunk.

   *Fig. 10. Completed branched lesson path*
