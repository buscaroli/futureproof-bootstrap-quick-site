# My Fave Recipe

Website about my favourite Recipe.

## Objective

This was a challenge given to me on day 3 of the Futureproof Bootcamp (Auguste cohort).

The focus of the site was to:

- use a CSS framework
- implement a responsive layout
- discuss with a team member the choices made and the pro and cons of using a framework (thanks [Layla](https://github.com/laylaSouthcombe) ⭐️)

## Technologies

The website was developed in a couple of hours, the technologies used include;

- HTML
- CSS
- Bootstrap 5

## Implementation

The website was implemented with HTML, CSS and Bootstrap 5.
The main layout has been designed mainly with **bootstrap grid** which has made it really easy to implement a responsive website.
The website was designed to be desktop-first.

- index.html was implemented as a two-columns responsive and fluid layout
- recipes.html was implemented as a three-column design responsive and fluid layout
- thanks.html was implemnted as a one column fluid layout
  \*\* in order to shrink the width of the column I have decided to use two side columns with no content. This way it would be easy to implement additional components later on (such as a aside)
- we were required to use media queries so I used two of them and have been careful to use the same breakpoints as Bootstrap

## PROS of using a CSS Framework (Bootstrap 5)

- a CSS framework can save a lot of time
- it is very easy to implement a responsive layout
- it provides tested components that look good by default

## CONS of using a CSS Framework (Bootstrap 5)

- it is difficult to create a website with your own style, it alwayl looks boxy and repetitive (as components are reused)
- there can be interaction with your own CSS stylesheet
  \*\* eg Bootstrap's own fs-1 class was interfering with the font size used in the media query so I had to remove it (there may be a better way of doing this but I couldn't find it within the given time)

## Feedback

- Due to the lack of time I didn't notice the Cards with the recipes didn't have any vertical margin, this has now been fixed.
- During the presentation it looked like the website was lagging while resizing the window. The instructor suggested to fix that problem and I found out that the problem wasn't in the website itself but that my computer was struggling because too many softwares were running in the background, including Zoom to share the video.
