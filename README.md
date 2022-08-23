# css-powered-personal-site

Purpose: Create a personal site that shows off my HTML/CSS ability.

Created as part of <u>The Complete 2022 Web Development Bootcamp</u><br>_(Section 5)_

---

## Source: [Udemy - The Complete 2022 Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp/)

## Instructor: [_Dr. Angela Yu_](https://www.appbrewery.co/)

---

## Things I learned in this section

**<u>Fonts:</u>** Font families are useful but when doing web design and a designer wants a specific typeset/font design, using the google fonts api is very useful to allow for a specific font to be utilized in the web design. I had previous experience with this concept but having additional exposure to this and actually watching Angela go through the process clued me into some interesting concepts. I noticed she set it up so that she only used the font weights she wanted (presumably to make download sizes even smaller) and that Google Fonts even offers a copy/paste for the code necessary to do the import correctly. Very useful. From an engineering standpoint, that's great because then I don't have to constantly remember HOW exactly to do this thing, but I can find the code and utilize it the way it needs to be done in my specific use case.

**<u>Dynamic Font Sizing:</u>** When using dynamic font sizing, the values you use in an element are added to any dynamic sizes used in parents. For example, if a `<body>` has a default `font-size` of `2em` (equivalent to `200%`), and a child `<div>` has a `font-size` of `3em` (equivalent to `300%`), the resulting font size would be `5em`/`500%`.

Using `rem` as a unit can circumvent this - as `rem` essentially tells the CSS styling to ignore all parent settings and change the font size relative to the root settings. This is the first time I've actually seen em and rem defined and their difference made obvious.

Note: _As far as font-size is concerned: `1em` === `100%` === `16px`_

---

**<u>Personal notes</u>**: This was a fun exercise to create a personal site from just HTML and CSS and figure out how to make it dynamic for use on mobile devices. I believe I did a pretty nice job. The toughest part of the whole thing so far has been figuring out how to make the margins and the various parts of the site fit together in both browser view and mobile view.

This exercise also helped me understand how to change the size of various elements in relationship to their parents and how that can be applied to a website. For example, the second container (light blue) is a full width container, but the children `<div>` elements all have various widths to make them more unique and in my eyes, appealing to read on both browser AND mobile.
