.. title: Help for /pages/legal-docs/ folder
.. slug: readme
.. date: 2025-02-17
.. tags: 
.. category: 
.. link: 
.. description: Provide the help for the /pages/legal-docs/ folder
.. type: text
.. hidetitle: True

.. _top:

/pages/legal-docs folder
------------------------

For Documents on legal and political matters written by Jeremy Dawson.

Ensure legal-docs.rst file includes the meta data:

\.\. slug: legal-docs

This folder is named *legal-docs*. It contains:

* **legal-docs.rst** - This is the document that is the introduction or overview of the legal and political documents that have been written.
* **/legal-docs/** - This is a folder. In this subfolder is where the writeup documents are placed.
* **README.rst** - This file you are now reading.


In the *conf.py* file the variable *NAVIGATION_ALT_LINKS* entry for *legal_docs.rst*:

  ```("/legal-docs/legal-docs/", "Legal"),```


The top level directory in Github *src* contains the *pages* folder which contains the *legal_docs* folder, which has the file *legal-docs.rst* and the folder *legal_docs*. 

When Gihub uses the *.github/workflows/main.yaml* the website the *legal-docs.rst* file in *main* becomes */legal-docs/legal-docs/index.html*

On a browser the *legal-docs.rst* file has the address:

  ```https://xxxxxx.github.io/legal-docs/legal-docs/index.html``` 
 

The file *legal_docs.rst* is the introductory or overview page for the legal documents and provides the links to these documents that are located in the */legal-docs/* sub-folder.

When adding new legal documents to the website, place them in *src* in the folder */legal-docs/legal-docs/*. If they are in *.rst* or *.md* format, then, upon making a github *commit*, they will be converted to *.html* files. When linking to the documents from *legal-docs.rst* the linking syntax as follows:

  To read the new document click \`here <new-document>`_

Which will display on the webpage as:

  To read the new document click `here <new-document>`_ 


Note on anonymous hyperlink target. 
-----------------------------------

In the text, a double-underscore suffix is used to indicate an anonymous hyperlink reference. In an anonymous hyperlink target, the reference text is not repeated. This is useful for references with long text or throw-away references, but the target should be kept close to the reference to prevent them going out of sync. 

`[Goto Top] <#top>`_
