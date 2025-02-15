files/files/ folder
-------------------

This files folder are intended for storing .pdf files that someone may want to download.

The extra file/ folder is design in "main" to create the top level folder "files".

Web pages are in sub-directories, so the syntax to reference a .pdf in files/files may be..

     ../../files/test.pdf

E.g.

.. code-block::
   :linenos

Click to download a pdf file...

     .. raw:: html

         <p>
         <a href="../../files/test.pdf" download>
         <button type="button">Click to download test.pdf file</button>
         </a>
         </p>
  

