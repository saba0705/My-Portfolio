User Story: 
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position


Acceptance Criteria:
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, and links to sections about them, their work, and how to contact them
I added semantics to my Html to target the functions.
I added <nav> to target the navigation bar to click and have the page scroll to the relative information
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
I added a pseudo class :hover with background shadow highlight so when the mouse hovers on the respective image, it's highlighted. 
I added my URL link to the Html and css so my projects can be viewed by viewing the website.

WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
I added @media queries to create the responsive layout and added styles to react when the viewport is resized. 
