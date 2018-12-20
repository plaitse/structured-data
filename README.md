# Structured data

## In theory

You can provide explicit informations about the meaning of your HTML page with structured data to classify the page content and to enable special search result features, for instance a graphical result - or a “rich result” like Google says - in a host carousel :

![Alt text](couscous-recipe.png?raw=true "Google graphical result")

The information precised in the structured data could be the ingredients for a recipe, or the materials needed to build an object or even the name of the chapters of a book.

One important point though, this structured data is not representative of the main content of the page. As Google says: it “enables a feature to be present, it does not guarantee that it will be present. The Google algorithm tailors search results to create what it thinks is the best search experience for a user, depending on many variables, including search history, location, and device type. In some cases it may determine that one feature is more appropriate than another, or even that a plain blue link is best.”

## In practice

In terms of code, it is simply a JavaScript-oriented object notation inside a ```<script>``` tag element in either the ```<head>``` or ```<body>``` of the page - that means basically anywhere in the page. It is hidden from the user.

Inside the ```<script>``` tag element, you can list properties to give Google more information about the thing being described. You don’t have to provide all of them but it means that it is less likely to work with Google features. The order of the properties don't matter.

First, set @context to http://schema.org to tell Google you're using schema.org structured data. Then, Set @type to what kind of thing you're describing: an article, a book, an event ors an organisation (company), etc.

## To verify

To see if your structured data is correctly implemented and doesn’t necessary properties, you can use Google testing tool: https://search.google.com/structured-data/testing-tool/u/0/ 

## Further info

- To see the full list of properties: https://developers.google.com/search/reference/overview 
- To see the full guideline: https://developers.google.com/search/docs/guides/sd-policies 
- To see another concrete example than mine: https://developers.google.com/search/docs/guides/intro-structured-data 
- To read more about Webmastering: https://support.google.com/webmasters/answer/35769 
