This repo provides a way to embed a Google Doc in an full-screen iframe. After a document is published, put the published document id as a GET parameter "docId" after the page url.

If that doesn't make sense to you, don't worry. If you load the page without specifying a document, it will ask you for a link, then change the URL to match. You can bookmark that URL to keep using it.

Example:

    `https://docs.google.com/document/d/e/2PACX-1vQfwjMYybecinG3lfzfdpU9ht-oKOVP-6EUZF6c-3kEvywKyzmu0kPvh49-jGyJ6tfSG0DJVMo0oJAt/pub"`

becomes

    `https://this-url?docId=2PACX-1vQfwjMYybecinG3lfzfdpU9ht-oKOVP-6EUZF6c-3kEvywKyzmu0kPvh49-jGyJ6tfSG0DJVMo0oJAt`
