# Information Extraction Demo App

This is a sample application for demonstrating how iKnow can not only be used to extract specific information
elements from natural language text, but also show which entities were involved and which other entities were
related to those supposedly containing the information, thereby often showing relevant contextual information.

## How to set up?
This app assumes you already have an iKnow domain configured (although you can also enter input text manually).
Simply refer your browser to http://localhost:57772/csp/user/Extractor.csp?123 with 57772, 'user' and 123 replaced
by the appropriate port number, namespace or web app name and domain ID, respectively.

## Extending the demo
This demo app was made to be extensible through the addition of (potentially code-heavy) Extractor classes.
Being designed for demo purposes, there may obviously be more elegant architectures than the current one.
