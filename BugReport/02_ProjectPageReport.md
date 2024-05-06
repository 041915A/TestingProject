
## Summary (Summarize the bug encountered concisely)

    The text for creating a new blank project has a typo.

## Steps to reproduce

    Go to the Login URL: https://gitlab.com/users/sign_in
    Log In With Username and Password
    Go to the New Project URL: https://gitlab.com/projects/new#

## What is the current bug behavior?

    The text displayed for creating a new blank project is "Create black project".

## What is the expected correct behavior?

    The text displayed for creating a new blank project should be "Create blank project".
     
## Relevant logs and/or screenshots

#### Bug Screenshot:
![Bug Screenshot](../Image/Bug_Create_Blank.png)

## Possible fixes

    Find the HTML element in the HTML file responsible for displaying the incorrect text. Edit the text in this element to correct the typo from "black" to "blank".

## Whom do you report/ Assign To/ Tags

      /label ~bug ~reproduced ~needs-investigation 
      /cc @project-manager 
      /assign @developer

## Priority

    Minor
