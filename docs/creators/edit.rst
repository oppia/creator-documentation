.. _edit:

Editing and Publishing a lesson
================================

In this section, you will learn how to:

* :ref:`Edit content <editingcontent>`
* :ref:`Work with older versions of your exploration <revert>`
* :ref:`Review errors and end your exploration <reviewerror>` 
* :ref:`Preview the exploration <preview>`
* :ref:`Save and publish the exploration <publish>`

Watch this video to learn how to edit and publish an exploration, or if you prefer reading the instructions instead, keep scrolling down.

.. raw:: html
   
   <iframe width="560" height="315" src="https://www.youtube.com/embed/ReMvCH531dg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

.. _editingcontent:

Editing content 
****************

1. In your exploration, you can navigate to different cards at any time by clicking on the card in the **Exploration Overview** section.

2. From here, you can make changes to any section within the card. To delete an entire card from the exploration, click on the small **x** in the top-right corner of the card.

.. figure:: /images/edit_content.png
   :alt: Editing content
   :scale: 35 %

   *Fig. 1*

3. To delete the entire exploration, go to the |settings| **Settings** button in the navigation bar, and click the |deleteexploration| button located at the bottom of the page.

.. |deleteexploration| image:: /images/delete_exploration.png
                       :alt: Delete Exploration button
                       :scale: 35 %

.. _revert:

Working with older versions of the exploration
**************************************************

1. Every time you save your exploration, Oppia keeps a record of that version. To save a draft of your exploration, click the |savedraft| button in the top navigation bar. In the pop-up box that appears, you can type in an optional message describing the changes made.

.. |savedraft| image:: /images/save_draft.png
               :scale: 40 %
               :alt: Save draft button

.. figure:: /images/save_description.png
   :alt: Save Draft box
   :scale: 40 %

   *Fig. 2*

2. You can view a list of all saved versions at any time by clicking the |history| **History** button.

.. |history| image:: /images/history_button.png
             :scale: 20 %
             :alt: History button

.. figure:: /images/history.png
   :alt: History of saved explorations

   *Fig. 3*

From the **History** screen, you have the following options:

.. topic:: Compare selected revisions

   Select any two previous versions and click the |compare| button to view what was changed.

   .. |compare| image:: /images/compare_revisions_button.png
                :scale: 40 %
                :alt: Compare selected revisions button

   .. figure:: /images/compare_versions.png
      :alt: Comparing two versions
      :scale: 30 %

      *Fig. 4*

.. topic:: Revert to a previously saved version

   Click the *Revert* link next to any version of your exploration to revert and go back to using that version. This change will now be recorded and added to your **History** under the list of changes.  

   .. warning:: When you revert to an older version, you will lose any unsaved changes in your exploration. If you think you might want to come back to your current version at some point later on, make sure you save your draft before reverting so that Oppia has a record of it. 

.. topic:: Download a version

   Click the *Download* link next to a version to download a zip file that will contain all the data for your exploration. It will include a YAML_ file as well as any additional asset files (such as images) that are part of your exploration. You can now share this file with other people if you wish.

   .. _YAML: https://en.wikipedia.org/wiki/YAML

   .. figure:: /images/revert_download.png
      :alt: Reverting and downloading past verions

      *Fig. 5*

.. _reviewerror:

Reviewing errors and ending the exploration
*********************************************

1. In the **Exploration Overview** section, you might see yellow warning signs next to the card(s). You need to resolve these warnings before you can publish your exploration. Hover your mouse over these signs to read the warning messages, then click on the card to resolve the issue.

.. figure:: /images/card_error.png
   :alt: Card warnings
   :scale: 35 %

   *Fig. 6*

2. Another common warning message tells you that you haven't properly ended your exploration. To do this, go to the last card of your exploration and click on the |add| button. In the pop-up box, click the **End Exploration** interaction button.

.. |add| image:: /images/add_interaction.png
         :scale: 30%
         :alt: Add Interaction button

.. figure:: /images/end_exploration.png
   :alt: End Exploration interaction
   :scale: 35 %

   *Fig. 7*

3. In the **Customize Interaction (End Exploration)** box, you can recommend :ref:`additional explorations <findid>` to the learner by clicking on the **Add exploration ID** button. Otherwise click the |saveinteraction| button to end the exploration.

.. |saveinteraction| image:: /images/save_interaction.png
                     :scale: 35%

.. figure:: /images/add_exploration_id.png
   :alt: Customize end exploration
   :scale: 35 %

   *Fig. 8*

.. _findid:

.. admonition:: Finding the ID of a published exploration

   To find the ID of an exploration, go to it and click on the |settings| **Settings** button in the navigation bar. Look under the title **Permissions** to find the exploration URL. The ID is the last string of characters that appears after '/explore/'.

   .. |settings| image:: /images/settings_button.png
                 :scale: 25 %
                 :alt: Settings button

   .. figure:: /images/exploration_id.png
      :alt: Exploration ID in a URL
      :scale: 35 %

      *Fig. 9*

.. _preview:

Previewing the exploration
***************************

1. To preview your exploration from the beginning, go to the first card in your exploration and click on the |preview| **Preview** button in the navigation bar. This shows you what it would look like to a learner. 

.. |preview| image:: /images/preview_button.png
             :alt: Preview button
             :scale: 20 %

.. figure:: /images/preview.png
   :alt: Preview mode

   *Fig. 10*

2. If you want to make changes at any time during the preview, click the |pencil| **Editor** button to return back to editing mode.

.. |pencil| image:: /images/pencil_icon.png
            :scale: 25 % 
            :alt: Editor button

.. _publish:

Saving and publishing
**********************

1. Save all changes in your exploration before publishing by clicking the |savedraft| button.

2. To publish the exploration, click the |publish| button.

.. |publish| image:: /images/publish.png
             :alt: Publish button
             :scale: 40 %

3. You will be asked to fill out additional details for your exploration such as a goal, a category, tags etc. Click on |savechanges| when done. 

.. |savechanges| image:: /images/save_changes.png
                 :alt: Save Changes button
                 :scale: 40 %

4. Finally, click the |publishexploration| button.

.. |publishexploration| image:: /images/publish_exploration.png
                        :alt: Publish Exploration button
                        :scale: 40 %

5. Once published, Oppia will display the URL for your exploration which will now be available in the Oppia library for anyone to learn. Congratulations!

.. figure:: /images/published_exploration_link.png
   :alt: Published exploration URL
   :scale: 40 %

   *Fig. 11*