# Natours
This is a static tour web project filled with dummy data. In this project:
*	CSS preprocessor (SASS) is applied. 
*	The folder architecture of SASS follows 7-1 pattern.
*	The naming convention for SASS is BEM methodology.

For responsive design, cross-browser and cross-device development:
*	Developer selected 4 breakpoints for different devices which includes large screen, tablet and phone. And in “most popular tours” section, considering user cannot trigger hover status of cards, developer shows both front side and back side.
*	Developer has done autoprefix for some experimental properties like perspective, so that animations can work on different browser. If some browsers cannot work, @support will be applied to show other content.
*	Responsive image technique is applied in footer and feature section. Browser downloads images according to viewport, pixel density and art direction.

For building and deployment:
*	Through compiling, concat with icon font, autoprefix and compression by dependencies in npm, the release version came out. 
*	This web app is deployed on firebase. URL is https://natours-2b9ee.web.app/.
