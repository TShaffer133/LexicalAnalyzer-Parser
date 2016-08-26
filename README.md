# LexicalAnalyzer-Parser

Note that the VMAssignment.c referred to in the user guide is not included within these files due to having no practical use with the output of the lexical analyzer and parser.

Errors that the Parser can detect:

No period at the end of a "block" of code

No identifiers after constant, variable, or procedure declaration.

No assignment symbol or numeric value for constants

Numeric assignment value is greater than 32767

No semicolon after declarations

No become statement following an identifier

No identifier after a call statement

No end statement following a begin statement denoting a block of code

No then statement following an if statement

No right parenthesis following a left parenthesis

An unknown math symbol was utilized (e.g. %)

Relation does not have a relational symbol (e.g. <, >, etc)

Possible Improvements:

Utilizing fgets instead of fscanf to prevent stack smashing
