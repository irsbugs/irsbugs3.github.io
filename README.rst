Information
-----------


>Tree of the source directory and its sub-directories and files. As of 2025-02-14.

> src                                           <-- Dir Source Code directory. Only edit files below. Do not edit files in "main" 
> ├── .github/workflows                         <-- Dir
> │   └── main.yml                              <-- Yaml command file for Github to run Nikola and re-build the website.
│
├── files                                     <-- Dir
│   ├── assets/css                            <-- Dir
│   │   └── custom.css                        <-- For adding additional CSS. E.g. Added indentation to blockquotes.
│   └── files                                 <-- Dir
│       ├── README.rst                        <-- Explanation of what this directory is used for.
│       └── test.pdf                          <-- Used by development to test Demo's download works OK.
│
├── images                                    <-- Dir
│   ├── jd-logo.svg                           <-- An svg file that contains the logo. Custom.css sets logo height.
│   └── julian_assange.jpg                    <-- Example picture used by Demo.
│
├── pages                                     <-- Dir
│   ├── legal-docs                            <-- Dir
│   │   ├── legal-docs                        <-- Dir
│   │   │   ├── README.rst                    <-- Explains that this directory is for .rst or .md files on legal matters.
│   │   │   ├── cm-contempt.rst               <-- Write-up file on Craig Murray.
│   │   │   ├── pcj-writeup.rst               <-- Write-up file on PCJ.
│   │   │   └── worden-writeup.rst            <-- Write-up file on Dr. Robert Worden.
│   │   ├── README.rst                        <-- Explains what this directory is for.
│   │   └── legal-docs.rst                    <-- This rst file is what the navigation button links to. Has the links to
│   │                                             to the write-up files in the subdirectory legal-docs
│   ├── streisand-docs                        <-- Dir
│   │   ├── streisand-docs                    <-- Dir
│   │   │   ├── README.rst                    <-- Explains that this directory is for .rst or .md files on Streisand Effect
│   │   │   ├── aaa-winstanley.rst            <-- Write-up file
│   │   │   ├── other-govt.rst                <-- Write-up file
│   │   │   ├── palestine-congress-notes.rst  <-- Write-up file
│   │   │   ├── palistine-congress.rst        <-- Write-up file
│   │   │   ├── social-media.rst              <-- Write-up file
│   │   │   ├── terrorism.rst                 <-- Write-up file
│   │   │   └── uk-police.rst                 <-- Write-up file
│   │   ├── README.rst                        <-- Explains what this directory is for.
│   │   └── streisand-docs.rst                <-- This rst file is what the navigation button links to. Has the links to
│   │                                             to the write-up files in the subdirectory streisand-docs
│   │
│   ├── about.rst                             <-- Jeremy's details. Displayed when clicking on the About button.
│   ├── demo.rst                              <-- Development demo file. To be hidden when development finished.
│   └── index.rst                             <-- The Welcome or Home page. Initial page that loads at the website.
│
├── .gitignore                                <-- Commands for Git. Don't touch.
└── conf.py                                   <-- The python program that Nikola runs to configure the website. It contains
                                                  many constants that you can change to modify the website.

