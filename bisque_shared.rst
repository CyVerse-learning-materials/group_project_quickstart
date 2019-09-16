.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

|Data_Commons_logo|_

Quickstart: Using CyVerse for a Shared Project 
===============================================

*Goal*
------

Set up a collaborative imaging project using CyVerse |Bisque|.

Prerequisites
-------------

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*


 .. list-table::
   :header-rows: 1

   * - Prerequisite
     - Preparation/Notes
     - Link/Download
   * - CyVerse account
     - You will need a CyVerse account to complete this exercise
     - |CyVerse User Portal|
   * - Bisque access
     - Request access to Bisque on the user portal
     - |CyVerse User Portal|

Platform(s)
~~~~~~~~~~~

*The following CyVerse platform(s) can be used in a collaborative project:*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Documentation
      - Quick Start
    * - Data Store
      - GUI/Command line
      - |Data Store|
      - |Data Store Manual|
      - |Data Store Guide|
    * - Discovery Environment
      - Web/Point-and-click
      - |Discovery Environment|
      - |DE Manual|
      - |Discovery Environment Guide|
    * - Bisque
      - Web/Point-and-click
      - |Bisque|
      - |Bisque Manual|
      - 

Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*No example data are required for this quickstart.*

----

*Get started*
--------------

1. Any project members who will be using CyVerse should take a look at the |Data Store Guide| and the |Discovery Environment Guide|. 
2. Be sure that all project members register for CyVerse accounts at the |CyVerse User Portal| and request access to Bisque. This action will create a directory in their home folder called `bisque_data`.

----

*Managing a shared Bisque project*
-------------------------------------

.. note::
		This quickstart is in progress. Please check back soon for the complete quickstart.


Managing a shared project with |Bisque| has some extra considerations, because image files are in Bisque are organized into  Datasets. Images files that are organized and shared using the Data Store (e.g., using the DE interface) can still be accessed via the image browser in Bisque, but they will not be organized as in the Data Store (add link to more in Bisque manual). If the Bisque web viewer or API are not needed, shared imaging projects can be managed using the |Data Store| just as for `Managing a regular group project <index.html>`_. Follow the guide below to decide how best to manage your project.

Choose the management workflow that best fits your project
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

CyVerse calls itself the "Lego building blocuks of cyberinfrastructure", which means there are dozens of ways to set up a shared imaging project. Below are some methods that we have found work well. If you have other suggestions, `please let us know <mailto:support@cyverse.org>`_!

Manage image data through the Bisque UI
+++++++++++++++++++++++

When is this a good option?
* Project members need to preview images
* Project members need to add graphical annotations
* Project uses Bisque apps for analyzing images



Manage image data through the Data Store in shared folder
+++++++++++++++++++++++


When is this a good option?
* Project data are shared only with project members

Manage image data through the Data Store in Community Released folder
+++++++++++++++++++++++

When is this a good option?
* Most of the project data are public

Sharing image data with project members
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

We strongly recommend that a single person be in charge of data management. There should also be a single person (generally the PI) who has ownership of the project folders and who sets read and write permissions for others. This ensures continuity when people move on. The PI can give ownership to a data manager for setting permissions, but should maintain their own ownership as well.

The owner of a folder has the ability to delete or rename the folder and any of its contents. If project members are given write permission to the project folder, they will be able to create their own sub-folders which they will own. In this way, project members can control access to their own data.

.. tip::
		Before beginning your project, make a plan for how to name files and organize datasets. Remember that like traditional folders, datasets in Bisque can be nested, so you can have one overarching dataset, with sub-datasets. Agree on which metadata are needed for each type of file, and set up protocols for adding metadata when files are uploaded. 

Sharing of images can be done through the |Bisque| interface or the |Discovery Environment| via the |data sharing feature| or on the command line using |iCommands|. Project members also can upload and download data using the desktop application |Cyberduck|, but Cyberduck cannot be used for setting sharing permissions.

According to the |CyVerse Data Policy|, all users receive a default allocation of 100GB. Shared data is counted as part of the allocation of whoever owns the folder that contains it. To request an increase to your allocation, should that become necessary, use the |allocation increase form|. We expect that users hosting shared directories will need to request larger data allocations.

If your project needs a shared folder for data that that going to be public during the active research phase of the project (e.g., you want to share transcriptomes or draft genomes as they are created, before publication), you can request a |Community Released Data Folder|. Community Released folders are intended for public data, not for shared projects that are kept private among collaborators.


Additional information, help
-------------------------------------

Search for an answer:
|CyVerse Learning Center| or
|CyVerse Wiki|

----

**Fix or improve this documentation**

- On Github: |Github Repo Link|
- Send feedback: `Tutorials@CyVerse.org <Tutorials@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

.. |Github Repo Link|  raw:: html

   <a href="https://github.com/CyVerse-learning-materials/group_project_quickstart" target="blank">Github Repo Link</a>

.. |Download Cyberduck| raw:: html

   <a href="https://cyberduck.io/" target="blank">Download Cyberduck</a>
   
.. |iCommands| raw:: html

   <a href="https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/step2.html" target="blank">iCommands</a>

.. |Cyberduck| raw:: html

   <a href="https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/step1.html" target="blank">Cyberduck</a>


.. |data sharing feature| raw:: html

   <a href="https://cyverse-data-store-guide.readthedocs-hosted.com/en/latest/step4.html#share-a-file-folder-in-discovery-enviornment-with-another-cyverse-user" target="blank">data sharing feature</a>
   
.. |CyVerse Data Policy| raw:: html

   <a href="https://www.cyverse.org/data-policy" target="blank">CyVerse Data Policy</a>
   
.. |allocation increase form| raw:: html

	<a href="https://user.cyverse.org/forms/2/overview" target="blank">allocation increase form</a>

.. |Creating a CyVerse Account| raw:: html

	<a href="https://learning.cyverse.org/projects/cyverse-account-creation-quickstart/en/latest/" target="blank">Creating a CyVerse Account</a>
	
.. |Community Released Data Folder| raw:: html

	<a href="https://wiki.cyverse.org/wiki/display/DC/Publishing+Data+through+the+Data+Commons" target="blank">Community Released Data Folder</a>

.. |Publishing your data through the CyVerse Data Commons| raw:: html

	<a href="https://wiki.cyverse.org/wiki/display/DC/Publishing+Data+through+the+Data+Commons" target="blank">Publishing your data through the CyVerse Data Commons</a>
	
.. |Pegasus| raw:: html

	<a href="https://pegasus.isi.edu/" target="blank">Pegasus</a>

.. |CyVerse Data Commons| raw:: html

	<a href="https://datacommons.cyverse.org/" target="blank">CyVerse Data Commons</a>

