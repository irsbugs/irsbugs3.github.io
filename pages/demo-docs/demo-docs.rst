.. title: Demo
.. slug: demo-docs
.. date: 2025-02-14
.. tags: 
.. category: 
.. link: 
.. description: Demonstrate some aspects of Nikola.
.. type: text
.. hidetitle: True

.. _top:

Demonstration of Nikola Static Website Features
===============================================

These examples are provided during development. If a feature is requested then the code needed may be copied from here. 
  
Feedback
========

As Nikola websites are static, they can not be publically written to. 

However there maybe times when you need a form to capture details from a person. A form is provided, then after collecting 
data it needs to be sent to another website whom provide the service of e-mailing the data to your e-mail address. 
This way your own personal e-mail address is not exposed in the source code of the webpage with the form. 

One vendor that provides this service is *Formspree*. 
Limitations are: Use Formspree for testing and development with unlimited projects and forms, limited to 50 submissions/month.

See: `Formspree <https://formspree.io/plans>`__.
  
Please provide the following information
----------------------------------------

.. raw:: html

    <!-- Add CSS for textarea to increase width -->
    <style>
        textarea {
          width: 80%;
          }
    </style>

    <form action="https://formspree.io/f/maylvdvn" method="POST">
 
        <div>Your First Name (required)</div>
        <input type="text" name="First Name" required />
        <br/>

        <div>Your Surname (required)</div>
        <input type="text" name="Surname" required />
        <br/>

        <div>Your E-Mail (required)</div>
        <input type="email" name="E-Mail Address" required />
        <br/>

        <div>Topic</div>
        <input type="text" name="Topic" />
        <br/>
        
        <!-- If rows and cols are not used then use CSS width and height
            rows="4" cols="100"-->
        <div>Write your comments and suggestions</div>
        <textarea name="Message"></textarea>

        <br/><br/>

        <button type="submit">Send</button>        
        
    </form> 

|
|

Downloading Files
=================

It is common to allow the downloading of files. Normally they are .pdf files.


.. comment:
    Making pdf files available for downloading:
    -------------------------------------------

    Change: conf.py from: FILES_FOLDERS = {'files': ''}
    to:  FILES_FOLDERS = {'files': 'files'}

    After the Nikola build, all the pdf files are placed into: /output/files/...

    Copy all pdf files into the files folder. E.g. test.pdf

    For a click-able link to the file that opens the download dialog box:
     
    <a href="/files/test.pdf" download>Download the pdf file: test.pdf</a>

Click to download a pdf file...

.. raw:: html

    <p>
    <!-- Split over 3 lines -->
    <a href="/files/test.pdf" download>
    <button type="button">Click to download test.pdf file</button>
    </a>
    </p>
  
|
|

Adding an Image to a document using reST
========================================

The reST code is: \.\. image:: /images/my_picture.jpg
Other externsions may be used. E.g. *.png*

The custom css file is in *src* folder */files/assets/css/custom.css*
Code in this file could set the size of the image.
  
Here is a picture of Julian Assange... 
  
.. image:: /images/julian_assange.jpg
       :width: 100
       :alt: Blind people. This is a photo of Julian
       :align: left

Julian is no longer in prison in London, England.

|  
|
|
|

`[Goto Top] <#top>`_
