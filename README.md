# Content-Management-Tool
1.HTML Structure:

The web page includes a title, a linked CSS file (style.css), and a container div.
It has a form for adding articles with input fields for the title and content.
There are buttons to add images, videos, images via URL, and videos via URL.
An empty table is provided to display articles.

2.JavaScript Functionality:

The code begins by selecting and storing references to various HTML elements and loading existing articles from localStorage.
There is a function called updateArticleTable to update the table displaying articles with data from storedArticles.
When the page loads, the updateArticleTable function is called to populate the table with existing articles.
The code listens for form submission to add new articles. When the form is submitted, it extracts the title and content, adds the article to storedArticles, and updates the table.
The code handles clicks on the table rows for editing and deleting articles. Clicking "Edit" populates the form fields with the article data, and clicking "Delete" removes the article from storedArticles.
There are event listeners for adding images and videos. When a user selects a file, the code displays the image or video in the article content.
There are event listeners for adding images and videos via URL. Users can input URLs, and the code adds images and videos accordingly.
A beforeunload event listener is used to save the content to localStorage before leaving the page.
