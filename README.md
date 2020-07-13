# Ian's Solution Methodology/Notes

Changed all <div> tags to semantic tags with a logical order <header>, <nav>, <main>, etc.

Tackled each semantic tagged section as an individual problem set. ie: I worked on the header first, then nav, then main, then footer, etc.

Created a single class for id elements that held identical CSS code, then consolidated all CSS tags into that single new class.

If I came across any strange formatting when I loaded the html into a browser, I reverted to a previous save without broken formatting and tried again to clean the code.

I maintained id tags to retain/enable nav button functionality.

IMPORTANT NOTE: CSS Parameters were never modified. Only consolidated into a new class tag or id tag. I found that class and id tag placement while in the HTML file was more conductive to success in this assignment.

Link to live website: git@github.com:iPan7/refactorhw.git

# 01 HTML CSS Git: Code Refactor

One of the most common tasks for front-end and junior developers is to take existing code and refactor it to either meet a certain set of standards or implement a new technology. Web accessibility is an increasingly important consideration for businesses, ensuring that people with disabilities or socio-economic restrictions have access to their website, and helping them avoid litigation.

Your task is to refactor an existing webpage to make it accessible. An important rule to follow when working with someone else's code is the Scout Rule:

> Always leave the code you are editing a little cleaner than you found it.

To impress clients, you should always go the extra mile and improve their codebase for long term sustainability. Ensure that all links are functioning correctly and clean up the CSS to make it more efficient, consolidating CSS selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

- - -
© 2019 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
