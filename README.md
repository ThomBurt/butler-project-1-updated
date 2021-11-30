# Code Refactor Starter Code

Changes:

-Change page title to ‘horrseon’
-Add ‘ID’ to social media marketing, as top link isnt working.
-Change semantics, ie: header, footer, sections.
PROBLEM:
When I add ‘sections’ semantics to the SEO, Online Reputation Management and Social Media Marketing box, the benefits box changes from being on the right, to being beneath everything.

Why?
I managed to fix it, as i noticed that another class was needed to keep them all to the left, that being <div class-”content”>
Added display:inline; to the .benefits class to try and move it up.
Noticed it has 2 classes, so seeing now if there any conflicts.
FIXED:
In HTML I moved the benefits box html to be above the other section! This has fixed the issue, while maintaining the section semantics. Is this because of sequential order?


-Slightly different for the alt in the image, as the image source is located in the CSS file.
The only way i found was to add a ‘title’ attribute on the div inside the html file.
