.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_


Data Management II
---------------------

    .. admonition:: learning-objectives

       - Know how to configure Cyberduck
       - Understand how Cyberduck works
       - Be able to upload a dataset using Cyberduck


**Description:**
In this module we will try to discuss the basic capabilities of the Data Store particularly how you can upload and download your dataset. This is done using Cyberduck, a 3rd party software that connects the Cyverse Data store to your local computer. This enables drag-and-drop download and upload of data from the Datastore to your local computer.
----

**Input Data:**

.. list-table::
    :header-rows: 1

    * - Input
      - Description
      - Example
    * -
      -
      -

*Upload data with Cyberduck*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. 	#### Comment: Step title should be descriptive (i.e. Cleaning Read data) ###


1. Download and install cyberduck https://cyberduck.io/download/ for your operating system.

2. Follow instructions 1-5 from the |Data Store Guide| to download and configure

   |Cyberduck|

   .. raw:: html


           <div>
           <iframe width="600" height="800" align="center" src="https://learning.cyverse.org/projects/data_store_guide/en/latest/step1.html#download-and-first-time-configuration-of-cyberduck" frameborder="0" style="border: 1px solid black;" allow="encrypted-media; gyroscope; " allowfullscreen></iframe>
           </div>

2. Upload the file **DE_sample_plants.fas** AND **README.txt** to your home folder in the Data Store.


*Upload data using the Discovery Environment*
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

1. If necessary, log into the CyVerse |Discovery Environment|.

2. Click on the |Data icon| (data icon) to access the Data window in the
   Discovery Environment.

3.  In the Data window you will see a directory of files and folders in your
    Data Store. You may select a folder to be the destination for your uploaded
    file(s). You may also click the Folder button to create a new folder. If
    you do not select a destination, files will be uploaded by default to your
    home Data Store folder (i.e., iplant/home/CYVERSE_USERNAME)

4. Click the Upload button to choose your options for importing files into the
   Discovery Environment:

   - To upload files from your local computer, choose Browse Local; a file
     browser will open and you may select files to upload (2 GB Max)
   - To upload files available at a URL, choose Import by URL; You may paste in
     a valid HTTP or an FTP URL. Then press Import. You may paste additional
     URLs or close this window by clicking Done.

5. Once you have begun the upload, you will get an automated notification that
   files have been queued for upload. You may also view the status of an upload
   or import by going back to the Upload button and choosing View Upload Queue.


**Output/Results**

.. list-table::
    :header-rows: 1

    * - Output
      - Description
      - Example
    * -
      -
      -


----

**Description of output and results**

----

Self Assessment Questions
````````````````````````````

  .. admonition:: Question
       :class: admonition-question

       Q1. Why do you need Cyberduck?

       A. To conveniently chat with CyVerse support
       B. To conveniently download and upload files from your local computer
       C. To conveniently create teams on the Discovery Environment
       D. To view apps and tools on the Discovery Environment


       .. admonition:: Answer

          Correct answer is B.


  .. admonition:: Question
       :class: admonition-question

       Q2. Select all that applies: Which of these will you need to configure and access the datastore using Cyberduck

       A. SSH access
       B. CyVerse account
       C. CyVerse cyberduck connection profile
       D. Discovery Environment


       .. admonition:: Answer

          Correct answer is B, C.

----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
- Send feedback: `learning@CyVerse.org <learning@CyVerse.org>`_

----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>
