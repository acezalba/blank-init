# blank-init

A Blank HTML-CSS Template for Beginners. With comments in HTML & CSS for well-organized code.

## What is it

This repository bundles the following:

- an `index.html` with:
  - browser and seo `meta` tags
  - stylesheet & script sections for:
    - development
    - production
  - `nav`, `header`, `main`, `aside`, and `footer` tags
- a basic `/asset` folder with:
  - a `/js` folder with a blank `script.js` file
  - an `/img` folder with a placeholder `favicon.ico`
  - a `css/style.css` with simple table of contents & sections for clean organized code
  - `Normalize.css` v8.0.1 for consistent defaults across browsers.

## How to use it

Easiest way is to download the zip to your computer or clone via `git clone`. Then modify and reuse to your heart's content.

**Beginner Tips:**

- place your project resources in the assets folder: `/img` for your images, `/css` for your stylesheets, and `/js` for your scripts. Place your css styles in the `style.css` file and your scripts in the `script.js` file.
- replace the `favicon.ico` in `assets/img/` with your own project favicon. The included icon is a sun emoji because sun. emoji.
- delete the `LICENSE` file. Now you are ready to use this for your projects.

## What is it for

I wanted a beginner's template that encourages a couple of best practices and observations online. A decent HTML5 boilerplate that I can simply copy-paste, for starters. The amazing [HTML5 Boilerplate](https://html5boilerplate.com/) feels a bit too overkill for basic portfolio projects, with some components (such as Modernizr) best managed through package managers.

I intend to use this blank-init as a base front-end template for blank and styled mockup repositories.

## Why separate sections for development and production in the html

Some front-end frameworks (looking at you Bootstrap) release versions of their files for development (verbose, uncompressed) and production (compressed, minified versions, hosted via CDN). As someone living in a place with horrid internet access, I found it helpful to download a local copy of these frameworks as well as set aside links to their online or minified versions.

The best way to take advantage of these sections is to copy CDN links of your chosen framework in the production stylesheet sections and link local versions in your development section. While developing, use your local version and comment out the links in your production section. And when readying your project for release, do it vice versa.

## TODO

- [] Preset media query breakpoints and debuggers
- [] An init-flexframe for a blank mockup with a responsive nav, header, and footer and gridflexbox defaults. (nav, header, and footer being the 'frame')
- [] A blank-init-bootstrap version with CDNs
- [] An init-mockup-business for mockup businesses sites
- [] An init-mockup-landing for a base landing page with sample content
- [] An init-mockup-blog for a set of responsive blog content templates and content
- [] An init-mockup-webapp for creating css mockups of web apps
- [] An intermediate init version designed for use with package managers and other web development toolchains

## License

- [Normalize.css](http://github.com/necolas/normalize.css) is covered under MIT License.
- The Sun Favicon is a placeholder emoji icon generated through [Favicon.io](http://favicon.io). Website by [John Sorrentino](https://twitter.com/johnsorrentino).
- Everything else is covered by the Unlicense (i.e. public domain.)
