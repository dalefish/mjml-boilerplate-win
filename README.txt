=============================================================
Massive credit to the guys at MJML, great tool http://mjml.io


| Author: Dale Mcconnell | Email: talk@dalemcconnell. co.uk |
=============================================================

====================
|Introduction
====================

A simple guide to setting up MJML using NPM and Sublime 3 on Windows

====================
|Requirements
====================

NPM
Local web server
Sublime 3

====================
|Installation
====================

Install MJML globally via NPM:

"npm install -g mjml"

Install MJML-syntax for Sublime 3

Under Tools in the menu make sure the Save All on Build is checked

Create Sublime 3 Custom Build Command:

{
	"shell_cmd": "mjml -r index.mjml -o index.html"
}

Save as MJML-build

Ensure the new build system is selected

Inside boilerplate.zip is the following file structure

content.mjml
footer.mjml
head.mjml
header.mjml
index.html
index.mjml
menu.mjml
pretext.mjml
social.mjml
sub-menu.mjml

Create a new folder for your project in your local working directory and unzip the content of boilerplate.zip

====================
|Usage
====================

1:) Begin coding!

2:) Whenever you are working in your index file or any of you partials, press Ctrl+B to build the whole project and render index.html

3:) View the page in your browser

4:) Rinse & repeat