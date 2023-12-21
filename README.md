# recipe search engine project "forkify"

This web app is a recipe search engine called "forkify". It allows users to search for over 1,000,000 recipes and bookmark their favorite ones. The app also has a feature that lets users add their own recipes.

HTML Structure

The HTML structure of the web app includes the following elements:
<!DOCTYPE html> declaration
<html> element with lang attribute set to "en"
<head> element containing:
<meta> tags for character encoding, viewport, and compatibility
<link> tags for Google Fonts and favicon
<script> tag for the controller JavaScript file
<title> tag for the page title
<body> element containing:
<header> element with logo, search form, and navigation menu
<div> element with class "search-results" for displaying search results and pagination
<div> element with class "recipe" for displaying recipe details
<div> elements for the overlay and add recipe window

CSS Styles

The CSS styles for the web app are located in the "src/sass/main.scss" file. The styles include:
General styles for typography, colors, and layout
Styles for the header, search form, navigation menu, and bookmarks list
Styles for the search results, pagination, and message/error states
Styles for the recipe details, ingredients, directions, and user-generated content
Styles for the overlay and add recipe window

JavaScript Functionality

The JavaScript functionality for the web app is located in the "src/js/controller.js" file. The functionality includes:

Event listeners for search form submission, navigation menu clicks, and bookmark button clicks
Functions for getting search results from the API, rendering search results and pagination, and handling errors and messages
Functions for getting recipe details from the API, rendering recipe details, and updating servings and bookmarks
Functions for showing and hiding the add recipe window, validating form input, and uploading new recipes to the API
Conclusion
Overall, this web app provides a simple and intuitive interface for searching and saving recipes. Its modular structure and well-organized code make it easy to maintain and extend.
