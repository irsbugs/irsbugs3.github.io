files/files/ folder
-------------------

This *files* folder is intended for storing .pdf files that someone may want to download.

The extra file/ folder is design so that in "main" it creates the top level folder "files".

Web pages are in sub-directories, so the syntax to reference a .pdf in files/files/ may be one of these...

.. code-block::

     ../files/test.pdf
     ../../files/test.pdf

For example:

.. code-block::
   :linenos

   Click to download a pdf file...

   .. raw:: html

        <p>
        <a href="../../files/test.pdf" download>
        <button type="button">Click to download test.pdf file</button>
        </a>
        </p>
  
This will be displayed on the web-page as:


Click to download a pdf file...

.. raw:: html

    <p>
    <a href="../files/test.pdf" download>
    <button type="button">Click to download test.pdf file</button>
    </a>
    </p>

