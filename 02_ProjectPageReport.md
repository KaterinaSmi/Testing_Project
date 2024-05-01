
## Summary (Summarize the bug encountered concisely)
     
     An incorrect label is displayed when user starts project creation. Users see "Create black project" instead of "Create blank project".

## Steps to reproduce

     Navigate to the project creation page.
     Look for the option "Create blank project."
     Observe the text displayed on the button/label.

## What is the current bug behavior?

     The text is incorrectly displayed as "Create black project" instead of "Create blank project."

## What is the expected correct behavior?

     The text should read "Create blank project," confirming that the current project is created without any templates or pre-configured elements.

## Relevant logs and/or screenshots

     Console Result:
     -Loading project creation page...
     -Loaded element with id 'create-blank-project' containing text 'create-black-project'
     JavaScript:
     -Source code (example):
     -Element: <button id="create-blank-project">Create black project</button>

## Possible fixes

     The likely fix is to correct the typo in the source code where the text is defined. This might be in a front-end component or localization file.

## Whom do you report/ Assign To/ Tags

     /label ~bug ~typo ~needs-investigation
     /cc @project-manager
     /assign @developer

## Priority

     Given that this is a user interface typo, the priority would likely be "Minor." However, if it impacts users' understanding of the functionality, it could be elevated to "Major."
     
      
