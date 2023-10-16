# jsdatelocaleformat
Javascript function to return the correct Locale format for a given Locale string

Javascript provides no way to fetch a Date format string for the user's language in a browser.  
This function uses navigator.language to return a Date format mask that you can use to correctly
display dates in your web application. 

I do not know of a reliable source for this data, so please send PRs if you believe something to be incorrect. 

Original Question:
https://stackoverflow.com/questions/2388115/get-locale-short-date-format-using-javascript/9893752

