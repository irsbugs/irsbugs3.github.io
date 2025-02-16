/pages/streisand-docs/ folder
------------------------

Top directory for documents on Streisand Effect written by Jeremy Dawson.

Ensure streisand-docs.rst file includes the meta data:

    .. slug: streisand-docs

This folder is named *streisand-docs*. It contains:

* **streisand-docs.rst** - This is the document that is the introduction or overview of the Streisand Effect 
documents that have been written.

* **/streisand-docs/** - This is a folder. In this subfolder is where the writeup documents are placed.

* **README.rst** - This file you are now reading.


In the *conf.py* file the variable *NAVIGATION_ALT_LINKS* entry for *streisand-docs.rst*:

  ```("/streisand-docs/streisand-docs/", "Streisand"),```


The top level directory in Github *src* contains the *pages* folder which contains the *streisand-docs* folder, 
which has the file *streisand-docs.rst* and the folder *streisand-docs*. 

When Gihub uses the *.github/workflows/main.yaml* the website the *streisand-docs.rst* file in *main* becomes 
*/streisand-docs/streisand-docs/index.html*

On a browser the *streisand-docs.rst* file has the address:

  ```https://xxxxxx.github.io/streisand-docs/streisand-docs/index.html``` 
 

The file *streisand-docs.rst* is the introductory or overview page for the legal documents and provides the links t
o these documents that are located in the *streisand-docs sub-folder*.

When adding new legal documents to the website, place them in *src* in the folder */streisand-docs/streisand-docs/*. 
If they are in *.rst* or *.md* format, then, upon making a github commit, they will be converted to *.html* files. 
When linking to the documents from *streisand-docs.rst* the linking syntax as follows:

  To read the new document click \`here <new-document>`_

Which will display on the webpage as:

  To read the new document click `here <new-document>`_ 


Note on anonymous hyperlink target. 
-----------------------------------

In the text, a double-underscore suffix is used to indicate an anonymous hyperlink reference. In an anonymous hyperlink 
target, the reference text is not repeated. This is useful for references with long text or throw-away references, but 
the target should be kept close to the reference to prevent them going out of sync. 

