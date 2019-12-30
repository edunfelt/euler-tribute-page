FreeCodeCamp Project: Tribute Page
=================

This is the [first project](https://www.freecodecamp.org/learn/responsive-web-design/responsive-web-design-projects/build-a-tribute-page) towards the Responsive Web Design Certificate on freeCodeCamp. The objective is to build a responsive tribute page using basic HTML, plain CSS and JavaScript, fulfilling the user stories below. The tests are ran using the tool in the upper left corner of the page by selecting the test suite *Tribute Page*.


Emilia Dunfelt, 2019 👩‍💻


[Website on GitHub Pages](https://edunfelt.github.io/euler-tribute-page/)

[![Remix on Glitch](https://cdn.glitch.com/2703baf2-b643-4da7-ab91-7ee2a2d00b5b%2Fremix-button.svg)](https://glitch.com/edit/#!/import/github/edunfelt/euler-tribute-page)


Techniques Used
------------------
The responsive collage is built using CSS Grid, with one layout for smaller devices (less than 600px), and one for larger devices. Inspiration was taken from an [excellent article](https://www.freecodecamp.org/news/how-to-create-an-image-gallery-with-css-grid-e0f0fd666a5c/) on freeCodeCamp on how to create an image gallery. I made the necessary changes to make the images take up all available space and responsively rezise. I also added hover CSS animations and text to make the grid more interesting. 

Originally I planned to have animations from the left and right as well, and not just from the top and bottom of the images, but the text inside the overlay resized to fit responsively during the animation, distracting the viewer. If you know a solution to this problem, please let me know.

Suggestions on ways to improve the look and feel of the project are welcome!


User Stories
--------------

1. My tribute page should have an element with a corresponding `id="main"`, which contains all other elements.
2. I should see an element with a corresponding `id="title"`, which contains a string (i.e. text) that describes the subject of the tribute page (e.g. "Dr. Norman Borlaug").
3. I should see a `div` element with a corresponding `id="img-div"`.
4. Within the `img-div element`, I should see an `img` element with a corresponding `id="image"`.
5. Within the `img-div element`, I should see an element with a corresponding `id="img-caption"` that contains textual content describing the image shown in `img-div`.
6. I should see an element with a corresponding `id="tribute-info"`, which contains textual content describing the subject of the tribute page.
7. I should see an a element with a corresponding `id="tribute-link"`, which links to an outside site that contains additional information about the subject of the tribute page.
8. The `img` element should responsively resize, relative to the width of its parent element, without exceeding its original size.
9. The `img` element should be centered within its parent element.
