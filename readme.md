The Tech Time Website
=====================

This is the source code for the tech time website.

It is rendered and published using [Quarto](https://quarto.org). The general workflow is:

1. Create a new Tech Time session in `/sessions`. If you are just adding a single page with no assets (i.e. are adding no images etc. to the repo) then you can just create a single `.qmd` file with the content. If you are adding a page with assets, then create a new directory in `/sessions` and add an `index.qmd` file to it. See `/sessions/why-rust/index.qmd` for an example.
2. Add the required metadata as yaml frontmatter to your `.qmd` file. The minimum requirements are:
  - title
  - date (should be the date of your Tech Time session)
  - description
  - categories
3. Use `quarto preview` and have a good look to make sure your new content looks right and that it is listed on the homepage.
4. Commit your changes and push upstream. **Please don't forget this step!**
5. Publish the site using `quarto publish gh-pages`.

Please see the [Quarto](https://quarto.org) documentation for further details. In particular note the the ability to publish Python, R, Julia, and Javascript notebooks with interactive output! It's awesome!

If you have any questions or problems then please contact Simon M.
