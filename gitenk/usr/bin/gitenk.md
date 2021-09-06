% GITENK(1) gitenk 0.1.5
% Roberto Carlos Medina
% September 2021

# NAME
gitenk - github token manager by local pc

# SYNOPSIS
**gitenk** [OPTION]\
**gitenk** *PARTNER*

# DESCRIPTION
**gitenk** allow's to push and make any action to Github, and also help's keep and mantain a personal Github token. Running **gitenk** without any command line parameters (subcommands) causes **gitenk** to display its version and his front presentation.

# OPTIONS
**help**
: Display a friendly help message.

**push**
: Display the output of the push being execute in while pushing to an repository.
**pull**
: Display the output of the force push being execute in while pushing to an repository.


**pull**
: Display the output of the pull being execute in while getting refresh from an repositor.

**change**
: Display some input message to enter the Github username and the personal token.
**-t**
: Display a input message to enter the personal token.
**-u**
: Display a input message to enter the Github username.

**show**
: Display a message that contain the username and the personal token.
**-t**
: Display message that contain the personal token.
**-u**
: Display a message that contain the Github username.


# EXAMPLES
**gitenk**
: Display version and gitenk front presentation.

**gitenk change -t**
: Display a input message to enter the new personal token.

**gitenk show -u**
: Display a message that contain the Github username.

**gitenk show**
: Display a message that contain the Github username and personal token.


# EXIT VALUES
**0**
: Sucess

**1**
: Invalid option

# BUGS
I  should think so.

# Author
Made by Roberto Carlos Medina. Email: robertocarlosmedina.dev@gmail.com

# COPYRIGHT 
©Copyright 2021 Roberto Carlos. This is a free software: you are free to change and redistribute it. There is NO WARRANTYm to the extent permitted by law.