.. include:: cyverse_rst_defined_substitutions.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

|Data_Commons_logo|_

Quickstart: Using CyVerse for a Shared Project 
===============================================


.. toctree::
	:maxdepth: 2

	Quickstart home <self>
	Shared projects on Bisque <bisque_shared.rst>


*Goal*
------

Learn the basic steps for setting up a collaborative project using CyVerse.

-----

*Prerequisites*
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
     - Be sure that all project members register for CyVerse accounts at the |CyVerse User Portal|. 
     - |Creating a CyVerse Account|

Platform(s)
~~~~~~~~~~~

*The following CyVerse platform(s) can be used in a collaborative project. Be sure all project members are familiar with them.*

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

.. tip::
		If your project is image based (i.e. you are sharing a lot of images), you may want to use |Bisque| to manage the data. If so, see the page on `Managing a shared Bisque project <bisque_shared.html>`_.


Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*No example data are required for this quickstart.*

----

*Get started*
--------------
**Make a plan.** You should have a `data management plan (DMP) <https://en.wikipedia.org/wiki/Data_management_plan>`_ before you begin your project. There are many resources on the web to guide you on how to create a DMP, including this `CyVerse documentation <https://learning.cyverse.org/projects/foss-2020/en/latest/Data_management/dmp.html>`_.

The most important DMP elements for this quick start are to know how you will organize your files and folders, what metadata you will use, and to make sure you have a *written SOP* for managing data.

.. tip::
		Before beginning your project, make a plan for how to name files and organize folders. Agree on which metadata are needed for each type of file, and set up protocols for adding metadata when files are uploaded. 

----

*Share data with project members*
-------------------------------------

Decide who has access to the data
~~~~~~~~~~~~~~~~~~~~~~~~~

There should be a single person (generally a PI) who has ownership of the project folders and who sets read and write permissions for others. This ensures continuity when people move on. The PI can delegate responsibility for setting permissions to a data manager, but should maintain their ownership of all folders as well.

The owner of a folder has the ability to delete or rename the folder and any of its contents. If project members are given write permission to the project folder, they will be able to create their own sub-folders which they will own. In this way, project members can control access to their own data.

.. warning::
		Anyone who has own permission on a folder can delete it or rename it!

For projects that are part of a single lab, we recommend that the PI create a CyVerse account, then create a project directory and share it with lab members. Specific sub-directories can be shared with specific lab members as desired.

For projects that are collaborations among multiple labs, one person should be create a project folder to share with all collaborators. Collaborators must decide among themselves who will host the main folder and who has read, write, and own permission for all folders. 

Create folders and set permissions
~~~~~~~~~~~~~~~~~~~~~~~~~~

Following the agreed upon folder hierarchy, create the base folders for your project and give read, write, or own permission to the appropriate project members

The sharing functionality the CyVerse Data Store can be used to share data among project members. This can be done through the |Discovery Environment| via the |data sharing feature| or on the command line using |iCommands|. Project members also can upload and download data using the desktop application |Cyberduck|, but Cyberduck cannot be used for setting sharing permissions.


.. tip::

	According to the |CyVerse Data Policy|, all users receive a default allocation of 100GB. Shared data is counted as part of the allocation of whoever owns the folder that contains it. To request an increase to your allocation, should that become necessary, use the |allocation increase form|. We expect that users hosting shared directories will need to request larger data allocations.

If your project needs a shared folder for data that that going to be public during the active research phase of the project (e.g., you want to share transcriptomes or draft genomes as they are created, before publication), you can request a |Community Released Data Folder|. Community Released folders are intended for public data, not for shared projects that are kept private among collaborators. See more below under *Publish data from a shared project*.

Use metadata to organize your files
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Folder hierarchies and file naming conventions can be an important part of managing a bit data project, but you cannot relay on them to make your data FAIR (findable, accessible, interoperable, and reusable). Good metadata not only makes your data FAIR, but make it easier for you to manage your project by making files searchable and understandable. 

CyVerse offers advanced metadata features for managing your data. See more details an `the CyVerse wiki metadata page <https://wiki.cyverse.org/wiki/display/DEmanual/Using+Metadata+in+the+DE>`_

*Share tools and analyses with project members*
---------------------------------------------------

Projects can use CyVerse analysis platforms to develop and share analysis tools and workflows.

The |Discovery Environment| (DE) contains hundreds of application that can be used by projects. Apps can be chained together to form workflows in the DE. It is now possible for CyVerse users to integrate their own applications or any open source application into the DE, using Docker containers. Projects may create private apps and workflows, to be shared only with project members, and then make those apps public when they are ready.

In the DE, you can create a team (*add link to documentation*) and share apps with your team.

|Atmosphere| can be used to set up a virtual machine (VM) with project software, which can then be used by all project members. The VM can later be imaged (made permanent) and published along with the project.

If your project includes a lot of computationally intensive analyses, you should consider requesting an XSEDE allocation (for the U.S. national super-computer infrastructure) and setting up HPC workflows using tools such as |Pegasus|. Compute intensive jobs that are highly parellel can be run on the Open Science Grid (`OSG <https://opensciencegrid.org/>`_) via the DE.

*Publish data from a shared project*
-------------------------------------
When you are ready to publish the results of your project, you should also publish the data to an appropriate repository. For sequence data, that is one of the INDSC repositories, such as NCBI's SRA. Other data types can be published to general scientific repositories or to the |CyVerse Data Commons|. See |Publishing your data through the CyVerse Data Commons|.

Group projects that are using a |Community Released Data Folder| to share data pre-publication are encouraged to transition to fully published data (with a DOI) when the data are stable. At that point, data can move into the Data Commons repository in its own folder, or it can remain within the shared project folder, but project members will lose edit access to the dataset. For more questions on this option, contact doi@cyverse.org.


*Additional information, help*
-------------------------------------



|Download Cyberduck|

----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
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

.. |Bisque| raw:: html

        <a href="https://bisque.cyverse.org/" target="blank">Bisque</a>
