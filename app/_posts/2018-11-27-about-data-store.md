---
layout: post
title: A Study of Data Store-based Home Automation
url: http://www.cs.wm.edu/~sgolden
tags:
    - Smart home Security
    - IoT Security
conference: In Proceedings of the 9th ACM Conference on Data and Application Security and Privacy (CODASPY)
---
Kafle, K., Moran, K., <b> Manandhar, S. </b>, Nadkarni, A., & Poshyvanyk, D. (2019). A Study of Data Store-based Home Automation. In Proceedings of the 9th ACM Conference on Data and Application Security and Privacy (CODASPY). Dallas, TX, USA. [<a href= "https://kaushalkafle.com/pdf/kafle-codaspy19.pdf"> PDF </a> ]

<!--more-->
<p style="color:#f5f5f5">
<h3> Abstract: </h3>
<div style="text-align: justify">
Home automation platforms provide a new level of convenience by enabling consumers to automate various aspects of physical objects in their homes. While the convenience is beneficial, security flaws in the platforms or integrated third-party products can have serious consequences for the integrity of a user’s physical environment. In this paper we perform a systematic security evaluation of two popular smart home platforms, Google’s Nest platform and Philips Hue, that implement home automation “routines” (i.e., trigger-action programs involving apps and devices) via manipulation of state variables in a centralized data store. Our semi-automated analysis examines, among other things, platform access control enforcement, the rigor of non-system enforcement procedures, and the potential for misuse of routines. This analysis results in ten key findings with serious security implications. For instance, we demonstrate the potential for the misuse of smart home routines in the Nest platform to perform a lateral privilege escalation, illustrate how Nest’s product review system is ineffective at preventing multiple stages of this attack that it examines, and demonstrate how emerging platforms may fail to provide even bare-minimum security by allowing apps to arbitrarily add/remove other apps from the user’s smart home. Our findings draw attention to the unique security challenges of platforms that execute routines via centralized data stores, and highlight the importance of enforcing security by design in emerging home automation platforms.
</div>
</p>
<!-- 
## Features

- Full-text search with [simple-jekyll-search](https://github.com/christian-fei/Simple-Jekyll-Search)
- Paginated home page
- Support for featured post images (appears on cards in previews)
- Threaded comments with Disqus
- Google Analytics integration

## Installation instructions

(Instructions are based off of those for the [Polymer Starter Kit](https://github.com/PolymerElements/polymer-starter-kit).)

- Clone this repository or download it as a .zip file and unzip.
- Install jekyll (and any other Ruby gems) with `bundle install`. (Prerequisite: must have Ruby installed. You may also have to install bundler with `gem install bundler`.)
- From the project root folder, run `npm install -g gulp bower && npm install && bower install`. (See the [Polymer Starter Kit installation instructions](https://github.com/PolymerElements/polymer-starter-kit#install-dependencies) for more details or troubleshooting.)

## Structure

- `app/`: All Jekyll content is here. (This is where all the editing happens)
  - `bower_components`: Content installed via bower ends up here
  - `elements/`: Custom web components using Polymer
  - `images/`: User images
  - 'media/': Other user content (PDFs, videos, etc.) for final product
  - `scripts/`: Javascript files
  - `styles/`: Custom CSS
- `dist/`: Built output from Gulp. (Use to publish static content)
- `node_modules`: Content installed via npm goes here

## Deployment

### Serve/watch

`gulp serve`: Starts a jekyll serve process on the default port (4000 or whatever is specified in `_config.yml`).

`gulp serve --port 6666`: Start serving on port `6666`

`gulp serve:dist`: Build as below, and serve the result from the `dist/` directory. (Useful for testing changes to the gulpfile.)

### Build and vulcanize

`gulp`: Builds the files with jekyll, vulcanizes, minimizes, and puts the result in the `dist/` directory. (This can be slow.)

## Deploy

`gulp deploy-gh-pages`: Deploy the current build to the gh-pages branch of your repository.

`gulp build-deploy-gh-pages`: Rebuild and then deploy. (Equivalent to `gulp && gulp deploy-gh-pages`)

## Future Improvements:

- Improve gulp build
    - Minimize JS, CSS, HTML
- Search
    - Ripple effect in search results on click (needs set height)
    - Escape toggles search show
    - arrow keys/tab moves focus on search results
    - better animation for search bar leaving/entering
- Navigation drawer
    - Change hover effect on drawer items (see Google Music)
    - Make selected/active items in drawer colored
- Page transition animations
- Give option of setting card-colorbar color
- Add ripple effect to nav drawer menu items
- Pagination:
    - Maybe replace with actual buttons
    - hover effects like buttons?
    - Handle if it gets too wide for screen? (limit number of page links)
- Tags
    - Show tags with posts
    - Allow filtering by tag
- Add material box or lightbox for images
- Add 'source' option for YAML frontmatter
- increase spacing between list items
- Fix things like header-panel to utilize updates to polymer paper elements

### Known issues

- JS and HTML aren't minimized
- Too much space on cards between end of excerpt and read more button
 -->
