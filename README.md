# Installation
1. Install Hugo as described in the [Quickstart guide](https://gohugo.io/getting-started/quick-start/)
2. Initialize the site with our forked module.

    hugo new site beka-new
    cd beka-new
    git init
    hugo mod init beka
    hugo mod get github.com/ajaquith/mediumish-gohugo-theme

    hugo server

3. Modify the template to include author info and favicons properly:

   - [Generate favicons](https://realfavicongenerator.net) using the SVG version of the logo and place into `static/images/favicons`. Create new partials in `layouts/partials/_shared` for `head.html` (which includes a new `favicons.html` partial) and the `favicons.html` partial, which adds meta links for the favicons.
    - Create new partial for the blog article tiles that properly creates the author name and image in `layouts/partials/list-partials/postbox.html`.
