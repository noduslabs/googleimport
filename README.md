googleimport
============

A Node.Js module with an API to import Google search results by a certain criteria.


#### 1. Objective ####

This Node.Js module should initiate a search on Google using the array of search terms provided and return search results back to the app that uses its API.

For example, when requested to do a search on `['network','analysis','software']` it should return the search results from Google, which contain all these terms (default: AND search).

These results should be returned as an array of objects, where each object is a search result snippet from Google, containing the following properties:
- Page Title
- Page URL
- text snippet from the page (obtained by Google search results)



#### 2. Initialization Algorithm ####

This should be a Node.Js module that can be used within any Node.Js application available in NPM repository.

The way it should work is that upon initiation from a Node.Js app such as

`var GoogleImport = require("google-import");`

it can then provide the results required through a call to one of its specific functions, such as

`var result = GoogleImport.getSearchResults(array, limit, searchtype);`

where `array` is an array of search terms, `limit` is the number of search results returned (optional, default - 50), `searchtype` - AND.




