.. _create:

Creating a new lesson
=====================

In this section, you will learn how to:

* :ref:`Create a new exploration<createexpl>`
* :ref:`Write the introduction<introduction>` 
* :ref:`Create content (questions)<createcontent>`
* :ref:`Add interactions (answers)<addinteractions>`
* :ref:`Add responses (feedback)<addresponses>`
* :ref:`Add hints to a question<addhints>`

Watch this video to learn how to create an :ref:`exploration<explorations>`, or if you prefer reading the instructions instead, keep scrolling down.

.. raw:: html
   
   <iframe width="560" height="315" src="https://www.youtube.com/embed/p_-gsK-zWNE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
   
.. _createexpl:

Create a new exploration
************************

1. To create a new exploration, from the Creator dashboard, click the **Create** button in the top right corner.

.. figure:: /images/create.png
   :alt: Creating a new exploration

   *Fig. 1*

2. You will see the Exploration Editor page. Now you will have to:
 * give your exploration a title
 * write the introduction 

.. figure:: /images/exploration_editor.png
  :alt: Exploration editor screen

  *Fig. 2*

3. To create a title for your exploration, click '**Untitled Exploration**' in the top left corner. This will take you to the **Settings** page. In the first field **Title**, type in a descriptive title for your exploration. We'll look at the other fields on this page in another section.

4. To get back to the Exploration editor page, click the |pencil| **Editor** button.

.. |pencil| image:: /images/pencil_icon.png
            :scale: 25 % 


.. figure:: /images/enter_title.png
  :alt: Entering title for exploration

  *Fig. 3*

.. _introduction:

Write the introduction
************************

.. admonition:: What to think about

   Your goal here is to engage or hook the learner to continue on with the exploration. Write as if you are having a conversation with the student. Introduce your topic, the protagonist of your story, or set the scene. You might also want to include:
   
    * what the student will already need to know beforehand
    * what they will need for this exploration (a paper, pen)

1. To begin writing the introduction, click inside the white box and begin typing. You will see different formatting options available to you. 

.. figure:: /images/introduction_card.png
  :alt: Creating the introduction card
  :scale: 30 %

  *Fig. 4*

2. When you're done writing the Introduction card, click the |save| button, then click the |add| button.

.. |save| image:: /images/save_content.png
          :scale: 35 %

.. |add| image:: /images/add_interaction.png
         :scale: 30%

3. A pop-up box will appear for you to choose an interaction. If you haven't yet asked a question to your reader in the Introduction card, you can select '**Continue Button**'. Interactions will be covered in more detail in the :ref:`Add Interactions<addinteractions>` section. 

.. _chooseinteraction:

.. figure:: /images/interactions.png
   :alt: Choosing an interaction
   :scale: 40 %

   *Fig. 5*

4. Edit the **Button label** if you wish and then click the |saveinteraction| button.

.. |saveinteraction| image:: /images/save_interaction.png
                     :scale: 35%

5. You will now see the '**Continue**' button below the Introduction card. Click on the bar below **Learner's Answers and Oppia's Responses** to direct what happens when the button is clicked.

6. To create a new card, click on the drop-down menu below **Oppia directs the learner to...** and select 'A New Card Called...'. Enter the name of the new card in the blank field and click on the |savedestination| button.

.. |savedestination| image:: /images/save_destination.png
                     :scale: 35 %

.. figure:: /images/newcard.png
   :alt: Creating a new card
   :scale: 40 %

   *Fig. 6*

7. The new card is now visible in the top-right section of the screen under **Exploration Overview**. Click on the card here to begin creating content.

.. figure:: /images/exploration_overview.png
   :alt: Exploration overview
   :scale: 50 %

   *Fig. 7*

.. _createcontent:

Create Content
****************

.. admonition:: What to think about

   It helps to have a specific question in mind that you want the learner to be able to answer at the end of the exploration. An example would be "What is the decimal equivalent of 1/2?" From here, come up with a series of questions and answers that will help the learner understand the concept of comparing fractions to decimals. This series of questions will form the main path of your exploration.

   Now, think about how you want to present your exploration. Do you want it in the form of a story? Try to characterize your cards as much as possible - is an authority figure asking the question? Is the learner helping a character out by answering? Students are much  more likely to remain engaged in this way as opposed to a rote question-answer card.

   When creating the exploration, focus on simplicity and create something linear (you can always add complexity later). Remember your goal with creating cards is to model a conversation between yourself and the student. 

There are four parts to a card:

1. Content
2. Interaction
3. Response
4. Hint

In this section, we'll focus on the :ref:`content<content>` where you will ask a question to the learner.

1. In the new card just created, click inside the white box to begin typing the content. The goal is to ask a question, so you may set the scene and then pose the question. When you're done, click the green |save| button.

.. topic:: Formatting Content

   The editor box gives you several formatting options including bolding, italicizing, inserting images, links, videos etc. As an example, you may choose to add an additional tab in this section to provide extra information using the '**Insert tabs**' button (if you want to provide a hint but not have it show up right away, see the :ref:`Add Hints<addhints>` section instead). This will end up looking like this:

   .. figure:: /images/Content_with_tab.png
      :alt: Editor box with tab inserted
      :scale: 40 %

      *Fig. 8*

.. _addinteractions:

Add Interactions
******************

.. admonition:: What to think about
   
   How do you want your learner to answer the question? Do you want them to type in an answer, or choose items from a selected list? Perhaps you want the learner to drag and drop items in a particular order. Oppia has several built-in interactions sorted by subject matter that you can choose from.

Now that you've posed a question, the next step is to add an :ref:`interaction<interaction>` - the type of answer the learner might give.

1. Click the |add| button.

2. The **Choose Interaction** :ref:`pop-up box<chooseinteraction>` appears. Click on the desired interaction which will bring up the **Customize Interaction** box. The customization options will depend on the type of interaction chosen. In the example below, we have selected the **Multiple Choice** interaction.

3. When you have finished customizing the Interaction, click on the |saveinteraction| button.

.. figure:: /images/customize_interaction.png
   :alt: Customize Interaction box
   :scale: 40 %

   *Fig. 9*

.. _addresponses:

Add Responses
*************

.. admonition:: What to think about
   
   The Response section is where you decide how Oppia should respond based on the learner's answer. Do you want the learner to redo the question or move them to a different card? If you want them to try again, include some constructive feedback about why the answer was wrong. Even if they have answered correctly, explain why the answer was right.


1. After you save an interaction, the **Add Response** pop-up box appears.

2. Choose the learner's possible answer, and add the appropriate response. To add a new response, click the |addanother| button. You can direct the learner to a new card based on a certain answer by creating one here. 

.. |addanother| image:: /images/save_add_another.png
                :scale: 35 %

.. figure:: /images/add_response.png
   :alt: Add response box
   :scale: 40 %

   *Fig. 10*

3. When you have finished adding responses, click the |saveresponse| button. This brings you back to the Editing screen where you can view the responses you've created. From here, you can add a new response, or edit or delete the responses you've created by clicking on the relevant box. 

.. |saveresponse| image:: /images/save_response.png
                  :scale: 35 %

.. admonition:: A word on Loopbacks
   
   When a learner answers incorrectly, there is an option to get the learner to 'try again' or loop back and answer the question again. It isn't always a good idea to do this. Think about whether you are able to group the possible 'wrong' answers in such a way that you can provide detailed feedback to the learner. 

   If you cannot do this, i.e., if the possible 'wrong' answers have come in through a text-field (so you have no way of knowing what the learner might type), or if there are lots of wrong answers to a question - it is better to send the learner to a separate branch to address their misconceptions. Looping them back to the question in this case might cause frustration as they will end up trying to guess what you want them to say.

.. _addhints:

Add Hints
*********

.. admonition:: When a Hint will appear
   
   To prevent learners from abusing the Hint feature, a hint can be requested only if **one** of the following conditions is satisfied:

    * The learner submitted a wrong answer at least once.
    * It has been more than 30 seconds since the learner last submitted an answer.

You may add one or more hints to a card in case the learner gets stuck. 

1. To add a hint to a card, click the |addhint| button at the bottom of the Editing screen.

.. |addhint| image:: /images/add_hint.png
              :scale: 35 %

2. The **Add Hint** pop-up box appears. Type in the hint and click the |savehint| button.

.. |savehint| image:: /images/save_hint.png
              :scale: 35 %

.. figure:: /images/addhint_box.png
   :alt: Add Hint box
   :scale: 40 %

   *Fig. 11*