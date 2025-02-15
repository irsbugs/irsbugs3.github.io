Welcome to Nikola Static Website Generator
==========================================

This website has been created using Github's ability to provide and run the Nikola application, and up to 120+ other 
applications that may be required.

It does not require a PC to have Nikola software installed and for the PC to *push* and *pull* files to Github.

The documents in the *src* (source) branch are the only ones that are edited to modifiy the website and any of its pages. 
After editing a file, click on *Commit* and the CPU's at Github will start running the applications to re-build the 
whole website. These *Updating* and *pages build and deployment* phases can be monitored by clicking on the *Actions* tab. 
The website re-build will take about 3 to 5 minutes before a refresh of a web-browser will display the updated website.

In some cases it is easier to write a document on a PC in reStructuredText *.rst* or Markdown *.md* and then upload this
file to a suitable folder in Github *src* branch.

For each *Commit* the website is re-built and located in the *main* branch. Do not edit any files in *main* branch as they 
will get replaced during the next *Commit* that is perform.

Tree of the *src* branch directory and its sub-directories and files. As of 2025-02-15.

```
src                                           <-- Dir Source Code top level branch directory.
│ 
├── .github/workflows                         <-- Dir
│   └── main.yml                              <-- Yaml. Runs Nikola to re-build the website.
│
├── files                                     <-- Dir
│   ├── assets/css                            <-- Dir
│   │   └── custom.css                        <-- For adding additional CSS. E.g. logo size.
│   └── files                                 <-- Dir
│       ├── README.rst                        <-- Explanation of what this directory is for.
│       └── test.pdf                          <-- Used by development to test Demo's downloads
│
├── images                                    <-- Dir
│   ├── favicon-16x16.png                     <-- Icons to insert in the web-browser tab
│   ├── favicon-32x32.png                     <-- 
│   ├── jd-logo.svg                           <-- An svg file that contains the logo.
│   └── julian_assange.jpg                    <-- Example picture used by Demo.
│
├── pages                                     <-- Dir
│   │ 
│   ├── about-docs                            <-- Dir
│   │   ├── about-docs                        <-- Dir
│   │   │   └── README.rst                    <-- Explains this directory is for "about".
│   │   ├── README.rst                        <-- Explains what this directory is for.
│   │   └── about-docs.rst                    <-- Write-up file that introduces Jeremy.
│   │ 
│   ├── demo-docs                             <-- Dir - Used in development only.
│   │   ├── demo-docs                         <-- Dir
│   │   │   └── README.rst                    <-- Explains this directory is for "demo".
│   │   ├── README.rst                        <-- Explains what this directory is for.
│   │   └── demo-docs.rst                     <-- reST file that introduces demo. By Ian.
│   │
│   ├── legal-docs                            <-- Dir
│   │   ├── legal-docs                        <-- Dir
│   │   │   ├── README.rst                    <-- Explains this directory is for legal matters.
│   │   │   ├── cm-contempt.rst               <-- Write-up file on Craig Murray.
│   │   │   ├── pcj-writeup.rst               <-- Write-up file on PCJ.
│   │   │   └── worden-writeup.rst            <-- Write-up file on Dr. Robert Worden.
│   │   ├── README.rst                        <-- Explains what this directory is for.
│   │   └── legal-docs.rst                    <-- Write-up file that introduces legal.
│   │                                         
│   ├── streisand-docs                        <-- Dir
│   │   ├── streisand-docs                    <-- Dir
│   │   │   ├── README.rst                    <-- Explains this directory is Streisand effects
│   │   │   ├── aaa-winstanley.rst            <-- Write-up file
│   │   │   ├── other-govt.rst                <-- Write-up file
│   │   │   ├── palestine-congress-notes.rst  <-- Write-up file
│   │   │   ├── palistine-congress.rst        <-- Write-up file
│   │   │   ├── social-media.rst              <-- Write-up file
│   │   │   ├── terrorism.rst                 <-- Write-up file
│   │   │   └── uk-police.rst                 <-- Write-up file
│   │   ├── README.rst                        <-- Explains what this directory is for.
│   │   └── streisand-docs.rst                <-- Write-up file that introduces streisand.
│   │
│   └── index.rst                             <-- Write-up file. The Welcome or Home page.
│
├── README.md                                 <-- Introduction to Nikola *src* branch. 
├── .gitignore                                <-- Commands for Git. Don't touch.
└── conf.py                                   <-- The python program that Nikola runs.
                                                  It contains many constants that you modify.
```


                                                  It contains many constants that you can use to modify the website.

