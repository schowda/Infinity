#  Classification of Periodic Table

This projects allows user to interact with the **Front End**, to access information  the elements and its properties in periodic table. Using Python-SPARQL API to run SPARQL queries against the Ontologies. We  have embed these queries  into Python-Flask RESTful Services. 

## FRONT END

Using HTML and Java Script, we were successfully able to create an Interative and attaractive UI. 

## BACK END

All the data is being pulled from a [ Periodic table Ontology](http://www.daml.org/2003/01/periodictable/) using Python-SPARQL API, You can find the API documentation in the attached project file.

## Additional Features

We have also tried to add some additional features for the project

- Un-meaningful selections in the UI displays a **No Matches Found**
- Example: 
     Selecting **Classification** as *Metallic*  and **Standard state** as *Gas* is not meaningfull and impossible to generate result.
- These errors were intimated using **No Matches Found**error messages eliminated 
