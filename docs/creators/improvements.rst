.. _improvements:

Improving a lesson
====================

In this section, you will learn how to make your exploration better by:

 * :ref:`Using the Improvements tab <improvementtab>`
         - :ref:`Getting feedback <feedback>`
         - :ref:`Suggestions for improvement <suggestions>`
         - :ref:`Answer details for a card <answerdetails>`
         - :ref:`Exiting early <earlyexit>`
         - :ref:`Multiple incorrect answers <incorrectanswer>`
         - :ref:`Getting stuck in a loop <cyclicloop>`
 * :ref:`Adding branches to an exploration <addbranch>`

Watch this video to learn how to improve your exploration, or if you prefer reading the instructions instead, keep scrolling down.

.. raw:: html

   <iframe width="560" height="315" src="https://www.youtube.com/embed/TnNdthvuWRQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

.. _improvementtab:

Using the Improvements tab
***************************

Oppia's explorations are designed to be improved over time as learners engage with the content. You can use the Improvements tab to determine how learners are using your exploration and what they think about it, and make changes accordingly.

1. Click the |improvements| **Improvements** button in the navigation menu. 
2. At the very top of the page, you can see how many **Open Tasks** are waiting for your review. 

.. note::

   By default, only *open* tasks are shown in the Improvements screen. If you want to see tasks that have been previously resolved, uncheck the **Show only "Open" tasks** box. This will show you any **feedback** or **suggestions** that you previously received on the exploration. All other tasks—once resolved—are permanently deleted.

   .. figure:: /images/show_hidden_task.png
      :alt: Show hidden tasks
      :scale: 30 %

      *Fig. 1*


The following are the types of open tasks you might see.

.. |improvements| image:: /images/improvements_tab.png
                  :alt: Improvements button
                  :scale: 30 %

.. _feedback:

Feedback on a card
-------------------

Learners have the option to provide feedback on each card as they play through an exploration, as well as at the end when they are asked to review the exploration. If they have provided any feedback, you will see a task similar to the image below.

.. figure:: /images/feedback_task.png
   :alt: Feedback task
   :scale: 40 %

   *Fig. 2*

1. To change the status of the feedback or write a message in response to the feedback for your record, click on the |reviewthread| button.
2. Click |sendandclose| when done.

.. caution:: 
   Leave the status at *Open* if you are still working on the task. Only use the other options if you want to hide the task from the Improvements screen.

.. |reviewthread| image:: /images/review_thread_button.png
                  :alt: Review Thread button
                  :scale: 40 %

.. figure:: /images/review_thread.png
   :alt: Review feedback message box
   :scale: 40 %

   *Fig. 3*

.. _suggestions:

Suggestions for a card
-----------------------

Learners also have the option to suggest an *edit* on one or more cards, e.g., a change in the content, formatting etc. This comes through as a *Suggestion* task in the Improvements screen.

.. figure:: /images/suggestion_task.png
   :alt: Suggestion task
   :scale: 40 %

   *Fig. 4*

1. Click the |reviewthread| button and then the |reviewsuggestion| button to take action on this suggestion.

.. |reviewsuggestion| image:: /images/review_suggestion_button.png
                      :alt: Review Suggestion button
                      :scale: 35 %

2. After reviewing the changes suggested by the learner, you can either accept or reject the suggestion.

.. figure:: /images/review_suggestion.png
   :alt: Review suggestion box
   :scale: 40 % 

   *Fig. 5*

3. Enter a new message if you wish to add to the message thread and change the status of the suggestion as required. Finally, click the |sendandclose| button. 

.. |sendandclose| image:: /images/send_and_close.png
                  :alt: Send and Close button
                  :scale: 40 %

.. figure:: /images/suggestion_message.png
   :alt: Suggestion message box
   :scale: 30 %

   *Fig. 6*

.. _answerdetails:

Answer details for a card
--------------------------

If you checkmarked the **Solicit Answer Details** box while creating your exploration, Oppia will occasionally ask a learner to explain why they chose a certain answer for that card.

.. figure:: /images/solicit_answer_details.png
   :alt: Solicit answer details checkbox
   :scale: 40 %

   *Fig. 7*

Whenever a learner explains why they chose their answer for a card, you will see the details in the Improvements screen as shown below.

.. figure:: /images/answer_details_task.png
   :alt: Answer details task
   :scale: 40 %

   *Fig. 8*

1. To review the details, click the |reviewanswerdetails| button and click under **Answer details** to expand the comment.

.. |reviewanswerdetails| image:: /images/review_answer_details.png
                         :alt: Review Answer Details box
                         :scale: 40 %

.. figure:: /images/answer_details_review.png
   :alt: Review answer details
   :scale: 40 %

   *Fig. 9*


2. To delete any **Answer details** received, checkmark the **Select** box next to each of them and click on the |deleteitems| box.

.. |deleteitems| image:: /images/delete_selected_items.png
                 :alt: Delete Selected items box
                 :scale: 40 %


.. admonition:: An example on improving an exploration

   Let's say you asked the question: **Which is greater: 0.834 or 0.2?** and requested an explanation from the learner for their answer. The learner selected the right answer, but explained they chose it because it was a longer number. This is obviously a misconception, so you may then decide to include additional cards beforehand or :ref:`branch out <addbranch>` to focus on place value or the decimal-fraction link.

.. _earlyexit:

Exiting a lesson early
-----------------------

Another issue you might see here is when a learner quits your exploration early without completing it to the end. 

.. figure:: /images/early_quit_playthrough.png
   :alt: Early Quit Playthrough task
   :scale: 35 %

   *Fig. 10*

Oppia will provide one or more sample playthroughs that will outline exactly how the learner proceeded through the exploration from start to finish.

1. To see exactly what the learner did, click on the green **View Playthrough** button.

.. figure:: /images/sample_playthrough.png
   :alt: Sample playthrough
   :scale: 40 %

   *Fig. 11*

2. To permanently remove the task from the Improvements tab, click the |resolved| button. 

.. |resolved| image:: /images/mark_as_resolved.png
              :alt: Mark as Resolved button
              :scale: 40 %

.. tip::
   Look out for patterns here—if learners seem to quit at one card in particular, then perhaps the difficulty level is too high, or the content is ambiguous.

.. _incorrectanswer:

Answering incorrectly multiple times
-------------------------------------

Oppia can also flag when a learner submits an incorrect answer several times on a card. 

.. figure:: /images/multiple_incorrect_task.png
   :alt: Multiple incorrect answer task
   :scale: 40 %

   *Fig. 12*

1. To see exactly what the learner did, click on the green **View Playthrough** button.

2. To permanently remove the task from the Improvements tab, click the |resolved| button. 

.. tip::
   If it makes sense, consider adding an incorrect answer in the **Learner's Answers and Oppia's Responses** section of the card. This will let you provide explicit feedback and may work particularly well with open-ended questions or cards with a 'Text Input' interaction.

   .. figure:: /images/answer_groups.png
      :alt: Adding a new response
      :scale: 45 %

      *Fig. 13*

.. _cyclicloop:

Revisiting the same card multiple times
----------------------------------------

If a card in your exploration loops back to an earlier card in case of an incorrect answer, a situation may arise where a learner keeps returning to the earlier card and gets stuck in a cyclic loop. This will appear in the Improvements screen as shown:

.. figure:: /images/cyclic_playthrough_task.png
   :alt: Cyclic playthrough task
   :scale: 40 %

   *Fig. 14*


1. To see exactly what the learner did, click on the green **View Playthrough** button.

.. figure:: /images/sample_cyclic_playthrough.png
   :alt: Sample Cyclic Playthrough
   :scale: 40 %

   *Fig. 15*

2. To permanently remove the task from the Improvements tab, click the |resolved| button. 

.. tip::
   If a learner keeps returning back to an earlier card, it appears they have not grasped the concept in that card. Consider rewriting the card to explain the concept more clearly, or provide more explicit feedback when they answer incorrectly. 

.. _addbranch:

Adding branches to an exploration
***********************************

When you first create an exploration, it's easiest to begin by creating a single series of questions and answers that might help a student understand the concept. This is the main 'trunk' of your lesson. You can start to add branches to this trunk as learners engage with your lesson and you notice certain patterns in the way they answer. 

For example, if many students are consistently getting the incorrect answer on one card in particular, you could redirect those students to a more elaborate explanation by sending them to a different branch (with one or more cards) which would eventually rejoin the main path of your exploration.

.. figure:: /images/adding_branches.png
   :alt: Figure showing exploration path and branch
   :align: center

   *Adding a branch to an exploration*

Let's look at an example where the learner is asked to compare decimal place values.

.. figure:: /images/question_card.png
   :alt: Exploration card question
   :scale: 40 %

   *Fig. 16*

If you notice quite a few students have been answering 'Hundredths' to this question, this is an indication that they are mistakenly equating place values for decimals with place values for whole numbers. To correct this misconception, you can branch out from this card and provide further explanation.

1. In Editor mode, go to the card in question and under **Learner's Answers and Oppia's Responses** click on the incorrect answer option (Hundredths). 

2. To branch out from this incorrect answer, click on the drop-down menu and select **A New Card Called...** Give the card a title and click on |savedestination|.

.. |savedestination| image:: /images/save_destination.png
                     :scale: 35 %
                     :alt: Save destination button

.. figure:: /images/creating_branch.png
   :alt: Creating new card
   :scale: 40 %

   *Fig. 17*

3. The new card is now visible in the **Exploration Overview** section. Click on this card to add content. 

.. figure:: /images/new_branch_card.png
   :alt: New card in Exploration Overview
   :scale: 40 %

   *Fig. 18*

You may choose to add several cards on this branch and then finally redirect the learner back to a card on the main path of the exploration. 

.. figure:: /images/complete_branch.png
   :alt: New branch in exploration overview
   :scale: 40 %

   *Fig. 19*