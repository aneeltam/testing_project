
## Summary (Summarize the bug encountered concisely)

There is a typo on the GitLab website on the Project page. Instead of 'Create blank project' it says 'Create black project'.

## Steps to reproduce     

Navigate to the GitLab project page
Find the option to create a new project
See the text indicating the creation of a new project

## What is the current bug behavior?

The text indicating the creation of a new project says 'Create black project' instead of 'Create blank project'.     

## What is the expected correct behavior?

The text is supposed to say 'Create blank project'.
     
## Relevant logs and/or screenshots

![Image info](../Image/Bug_Project_create_blank.png)
      
## Possible fixes

Fix the typo in the Project page's code. Search for 'black project'.

## Whom do you report/ Assign To/ Tags

/label ~bug ~reproduced ~needs-investigation 
/cc @project-manager 
/assign @qa-tester

## Priority

The priority level for the bug is minor. The Project page is still usable, but it does intervene in the user's experience of using the page.