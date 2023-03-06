# Ivy

Ivy is an artefact management system designed to help collaborate and manage the 
many files, requirements, documents, builds and other such artefacts that are created
in the software development process.

## How does it work?

Ivy will track the changes to a specific artefact. It will keep a record of
who, why and where a change was made. It will also provide the ability to view
the artefacts at any point in their history.

Ivy makes use of a tag and property system to organize and sort the artefacts
stored within the repository. Apply these tags and properties and then make use
of a SQL style command structure to filter and display content.

Ivy will also provide a link system that will allow users to connect related
artefacts. This will provide further context in organization and grouping of 
artefacts.

Ivy will provide have a set of identifiable artefacts that if their internal
content matches a predescribed standard, Ivy will be able to provide further
functionallity with those artefacts. 

## Styleguide

This project will ascribe to idoimatic rust in both implementation and style as
much as possible. If there exists a necessary case to break these rules, they can
be found in docs/styleguide.md
