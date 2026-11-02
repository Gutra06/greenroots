# GreenRoots Community Garden

## Project Overview

GreenRoots is a static website project for a community garden initiative. It presents the garden's programs, events, volunteer opportunities, donation information, and environmental learning resources.

## Website Features

- Homepage introducing GreenRoots, its programs, garden locations, and community activities.
- Volunteer page with opportunities and a sign-up form.
- Donation page describing ways to support the gardens and linking to downloadable PDF resources.
- Shared responsive styling for navigation, headings, buttons, cards, forms, and page sections.

## Styling Improvements

In the first submission, my  CSS was not able to  style the HTML as i had  intended it to, so the pages appeared mostly unstyled. The original stylesheet used selectors that did not match the page markup, stylesheet references were inconsistent, and inline styles overrode some CSS rules.

The new `greenroots.css` stylesheet provides a consistent visual design with forest-green colors, clear typography, a garden photo hero, structured content layouts, accessible focus states, and mobile breakpoints. The main GreenRoots pages now reference this stylesheet.

## Donation PDF Resources

The donation page includes links to these project resources:

- `2 What to Grow_Web.pdf`
- `SPowell_CGC-Garden-Manual-Final.pdf`
- `Smit_GoghariQgjw.pdf`

by keeping  the PDFs in the same folder as `donate.html`, which allows users to be able to can access to these files all located in the donate.html .Before sharing the website on another computer or hosting it online, change the PDF links in `donate.html` to relative paths, since they currently contain local Windows file paths.

## Running the Website

Open `Website.html` in a web browser.  with The site using  plain HTML, CSS, and JavaScript and does not require a build step. Keep the HTML files, `greenroots.css`, images, PDFs, and `js` folder together so the referenced assets are able to be found.

## Current Limitations

- The donation and volunteer forms are front-end examples and do not save submissions to a database.
- The PayPal form contains a placeholder button ID that must be replaced with a real hosted donation button ID before accepting payments.
- Some page content and file paths may need further proofreading and testing before public deployment.
