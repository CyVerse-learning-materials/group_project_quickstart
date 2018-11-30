.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

|Data_Commons_logo|_

Quickstart: Using CyVerse for a Shared Project 
===================

*Goal*
----

Learn the basic steps for setting up a collaborative project using CyVerse.

-----

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

Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*No example data are required for this quickstart.*

----

*Get started*
--------------

1. Any project members who will be using CyVerse should take a look at the |Data Store Guide| and the |Discovery Environment Guide|. You may also want to review the |Atmosphere Guide|.
2. Be sure that all project members register for CyVerse accounts at the |CyVerse User Portal|. See |Creating a CyVerse Account|.

----

*Sharing data with project members*
--------------

For projects that are part of a single lab, we recommend that the PI create a CyVerse account and share it with lab members. Specific sub-directories can be shared with specific lab members as desired.

For projects that are collaborations among multiple labs, one person should be create a project folder to share with all collaborators. Collaborators must decide among themselves who has read, write, and own permission. 

.. tip::
		Anyone who has own permission on a folder can delete it or rename it!

The sharing functionality the CyVerse Data Store can be used to share data among project members. This can be done through the |Discovery Environment| via the |data sharing feature| or on the command line using |iCommands|. Project members also can upload and download data using the desktop application |Cyberduck|, but Cyberduck cannot be used for setting sharing permissions.

According to the |CyVerse Data Policy|, all users receive a default allocation of 100GB. Shared data is counted as part of the allocation of whoever owns the folder that contains it. To request an increase to your allocation, should that become necessary, use the |allocation increase form|. We expect that users hosting shared directories will need to request larger data allocations.

If your project needs a shared folder for data that will be made public, you can request a |Community Released Data Folder|. Community Released folders are intended for public data, not for shared projects that are kept private.

Managing data in a shared project
~~~~~~~~~~~~~~~~~~~~~~
We strongly recommend that a single person be in charge of data management. There should also be a single person (generally the PI) who has ownership of the project folders and who sets read and write permissions for others. This ensures continuity when people move on. The PI can give ownership to a data manager for setting permissions, but should maintain their own ownership as well.

The owner of a folder has the ability to delete or rename the folder and any of its contents. If project members are given write permission to the project folder, they will be able to create their own sub-folders which they will own. In this way, project members can control access to their own data.

*Sharing tools and analyses with project members*
--------------

Projects can use CyVerse analysis platforms to develop and share analysis tools and workflows.

The |Discovery Environment| (DE) contains hundreds of application that can be used by projects. Apps can be chained together to form workflows in the DE. It is now possible for CyVerse users to integrate their own applications or any open source application into the DE, using Docker containers. Projects may create private apps and workflows, to be shared only with project members, and then make those apps public when they are ready.

|Atmosphere| can be used to set up a virtual machine (VM) with project software, which can then be used by all project members. The VM can later be imaged (made permanent) and published along with the project.

If your project includes a lot of computationally intensive analyses, you should consider requesting an XSEDE allocation (for the U.S. national super-computer infrastructure) and setting up HPC workflows using tools such as |Pegasus|.

Additional information, help
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Search for an answer:
|CyVerse Learning Center| or
|CyVerse Wiki|

Post your question to the user forum:
|Ask CyVerse|

|Download Cyberduck|

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
   
.. |allocation increase form|
	<a href="https://user.cyverse.org/forms/2/overview" target="blank">allocation increase form</a>

.. |Creating a CyVerse Account| raw:: html
	<a href="https://learning.cyverse.org/projects/cyverse-account-creation-quickstart/en/latest/" target="blank">Creating a CyVerse Account</a>
	
.. |Community Released Data Folder| raw:: html
	<a href="https://wiki.cyverse.org/wiki/display/DC/Publishing+Data+through+the+Data+Commons" target="blank">Community Released Data Folder</a>
	
.. |Pegasus| raw:: html
	<a href="https://pegasus.isi.edu/" target="blank">Pegasus</a>
