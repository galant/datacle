Datacle
=======

Data tags that journalists can easily use to make articles more relevant for their readers. 

What if all news really was local? Journalists can drop datacle tags into their articles that will display data from databases based on characteristics of the reader. For example, in article about a congressional bill can tell the reader how their congressperson voted. 


=======

Here's how a journalist can use it:

1. Install our javascript

2. Select a database

3. Put datacle tags in your stories
Write the tag in this format: {{query.databasename.fieldname}}
Example modifying this [New York Times article](http://www.nytimes.com/2014/05/23/us/politics/house-votes-to-limit-nsas-collection-of-phone-data.html):
	In a rare moment of bipartisan agreement between the White House and Congress on a major national security issue, the House passed legislation on Thursday that aims to end the National Security Agency’s bulk phone records program that had prompted intense domestic debate about privacy and civil liberties.
{{local.congressman.name}} voted {{local.congressman.rollcall230}}.
