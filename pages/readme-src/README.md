---
title: README for src top-level folder.
slug: readme
date: 2025-02-17
tags: 
category: 
link: 
description: /pages/readme-src/README.rst can not be in top-level as html file in top-level is index.html. i.e. Home Page
type: text
hidetitle: True
---

<a id="Top"></a>

Welcome to Nikola Static Website Generator
==========================================

This website has been created using Github's ability to provide and run the Nikola 
application, and up to 120+ other applications that may be required.

It does not require a PC to have Nikola software installed and for the PC to *push* and 
*pull* files to Github.

The documents in the *src* (source) branch are the only ones that are edited to modifiy the 
website and any of its pages. After editing a file, click on *Commit* and the CPU's at 
Github will start running the applications to re-build the whole website. These *Updating* 
and *pages build and deployment* phases can be monitored by clicking on the *Actions* tab. 
The website re-build will take about 3 to 5 minutes before a refresh of a web-browser will 
display the updated website.

In some cases it is easier to write a document on a PC in reStructuredText *.rst* or 
Markdown *.md* and then upload this file to a suitable folder in Github *src* branch.

For each *Commit* the website is re-built and located in the *main* branch. Do not edit any 
files in *main* branch as they will get replaced during the next *Commit* that is perform.

The src top-level directory has 4 x folders and 3 x files. The three files are:

```
.gitignore <--- Command for *git*. Dont change this file.
README.rst <--- The file you are now reading.
conf.py    <--- This python configuration file performs the loading of constants that are
                used by Nikola every time the website is re-built. 
```

**Tree diagram of the *src* branch directory and its sub-directories and files.** - 2025-02-17

<p style="line-height: 0.99em; font-family: monospace, monospace;">
src <-- Dir Source Code top level branch directory. <br> 
│ <br> 
├── .github/workflows <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;└── main.yml <-- Yaml. Runs Nikola to re-build the website.
│ <br> 
├── files <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;├── assets/css <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── custom.css <-- For adding additional CSS. E.g. logo size. <br> 
│&nbsp;&nbsp;&nbsp;└── files <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── test.pdf <-- Used by development to test Demo's downloads <br> 
│ <br> 
├── images <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;├── favicon-16x16.png <-- Icons to insert in the web-browser tab <br> 
│&nbsp;&nbsp;&nbsp;├── favicon-32x32.png <-- <br> 
│&nbsp;&nbsp;&nbsp;├── jd-logo.svg <-- An svg file that contains the logo. <br> 
│&nbsp;&nbsp;&nbsp;└── julian_assange.jpg <-- Example picture used by Demo. <br> 
│ <br> 
├── pages <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── about-docs <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── about-docs <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── about-docs.rst <-- Write-up file that introduces Jeremy. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── demo-docs <-- Dir - Used in development only. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── demo-docs <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── demo-docs.rst <-- reST file that introduces demo. By Ian. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── legal-docs <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── legal-docs <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── cm-contempt.rst <-- Write-up file on Craig Murray. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── pcj-writeup.rst <-- Write-up file on PCJ. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── worden-writeup.rst <-- Write-up file on Dr. Robert Worden. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── legal-docs.rst <-- Write-up file that introduces legal. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── streisand-docs <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── streisand-docs <-- Dir <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── aaa-winstanley.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── other-govt.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── palestine-congress-notes.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── palistine-congress.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── social-media.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── terrorism.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── uk-police.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── streisand-docs.rst <-- Write-up file that introduces streisand. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;└── index.rst <-- Write-up file. The Welcome or Home page. <br> 
│ <br> 
├── .gitignore <-- Commands for Git. Don't touch. <br> 
└── conf.py <-- The python program that Nikola runs. It contains many constants that you modify. <br>
</p>

Every directory has a README.rst file that contains a brief explanation of what is in that
directory. These README.rst files are omitted in the above tree diagram to make it 
easier to comprehend the diagram. Although the README files are passed to the "main"
branch their contents are not displayed by the website.

<p style="line-height: 0.99em; font-family: monospace, monospace;">
src <-- Dir Source Code top level branch directory. <br> 
│ <br> 
├── .github/workflows <br> 
│&nbsp;&nbsp;&nbsp;└── main.yml <-- Yaml. Runs Nikola to re-build the website. <br>
│ <br> 
├── files <br> 
│&nbsp;&nbsp;&nbsp;├── assets/css <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── custom.css <-- For adding additional CSS. E.g. logo size. <br> 
│&nbsp;&nbsp;&nbsp;└── files <br> 
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── test.pdf <-- Used by development to test Demo's downloads <br> 
│ <br> 
├── images <br> 
│&nbsp;&nbsp;&nbsp;├── favicon-16x16.png <-- Icons to insert in the web-browser tab <br> 
│&nbsp;&nbsp;&nbsp;├── favicon-32x32.png <-- <br> 
│&nbsp;&nbsp;&nbsp;├── jd-logo.svg <-- An svg file that contains the logo. <br> 
│&nbsp;&nbsp;&nbsp;└── julian_assange.jpg <-- Example picture used by Demo. <br> 
│ <br> 
├── pages <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── about-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── about-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── about-docs.rst <-- Write-up file that introduces Jeremy. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── demo-docs <-- Dir - Used in development only. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── demo-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── demo-docs.rst <-- reST file that introduces demo. By Ian. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── legal-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── legal-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── cm-contempt.rst <-- Write-up file on Craig Murray. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── pcj-writeup.rst <-- Write-up file on PCJ. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── worden-writeup.rst <-- Write-up file on Dr. Robert Worden. <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── legal-docs.rst <-- Write-up file that introduces legal. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── streisand-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── streisand-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── aaa-winstanley.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── other-govt.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── palestine-congress-notes.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── palistine-congress.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── social-media.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── terrorism.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── uk-police.rst <-- Write-up file <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── streisand-docs.rst <- Write-up file that introduces streisand. <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;└── index.rst <-- Write-up file. The Welcome or Home page. <br> 
│ <br> 
├── .gitignore <-- Commands for Git. Don't touch. <br> 
└── conf.py <-- The python program that Nikola runs. It contains many constants that you modify. <br>
</p>

<p style="line-height: 0.99em; font-family: monospace, monospace;">
src <br> 
│ <br> 
├── .github/workflows <br> 
│&nbsp;&nbsp;&nbsp;└── main.yml <br>
│ <br> 
├── files <br> 
│&nbsp;&nbsp;&nbsp;├── assets/css <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── custom.css <br> 
│&nbsp;&nbsp;&nbsp;└── files <br> 
│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── test.pdf <br> 
│ <br> 
├── images <br> 
│&nbsp;&nbsp;&nbsp;├── favicon-16x16.png <br> 
│&nbsp;&nbsp;&nbsp;├── favicon-32x32.png
│&nbsp;&nbsp;&nbsp;├── jd-logo.svg <br> 
│&nbsp;&nbsp;&nbsp;└── julian_assange.jpg <br> 
│ <br> 
├── pages <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── about-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── about-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── about-docs.rst <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── demo-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── demo-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── demo-docs.rst <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── legal-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── legal-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── cm-contempt.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── pcj-writeup.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── worden-writeup.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── legal-docs.rst <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;├── streisand-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── streisand-docs <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── aaa-winstanley.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── other-govt.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── palestine-congress-notes.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── palistine-congress.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── social-media.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;├── terrorism.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── uk-police.rst <br> 
│&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;└── streisand-docs.rst <br> 
│&nbsp;&nbsp;&nbsp;│ <br> 
│&nbsp;&nbsp;&nbsp;└── index.rst <br> 
│ <br> 
├── .gitignore <br> 
└── conf.py <br>
</p>
Metadata Template for .rst files
--------------------------------

All *reStructuredText .rst* filenames should only use **a to z**, **0-9** and a literal dash **-**.

This is what the *slug* metadata expects.

When creating a new .rst file copy and paste the template below:
```
.. title: *My Title
.. slug: *name of file without .rst extension.
.. date: *2025-02-14
.. tags: 
.. category: 
.. link: 
.. description: *Write description
.. type: text
.. hidetitle: True

.. _top:

Write or Paste your document here...

`[Goto Top] <#top>`_

```

Metadata Template for .md files
-------------------------------

All *markdown .md* filenames should only use **a to z**, **0-9** and a literal dash **-**.

This is what the *slug* metadata expects.

When creating a new .md file copy and paste the template below:

```
title: *My Title
slug: *name of file without .rst extension.
date: *2025-02-15
tags: 
category: 
link: 
description: *Write description 
type: text
hidetitle: true

<a id="Top"></a>


Write or Paste your document here...


<br><hr>
[Goto Top](#top)
```

[Goto Top](#top)
