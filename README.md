# Minimal Mistakes remote theme starter

Click [**Use this template**](https://github.com/mmistakes/mm-github-pages-starter/generate) button above for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes).

Contains basic configuration to get you a site with:

- Sample posts.
- Sample top navigation.
- Sample author sidebar with social links.
- Sample footer links.
- Paginated home page.
- Archive pages for posts grouped by year, category, and tag.
- Sample about page.
- Sample 404 page.
- Site wide search.

Replace sample content with your own and [configure as necessary](https://mmistakes.github.io/minimal-mistakes/docs/configuration/).

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.


## Customization
- [Documentation](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)
- Not all theme files are included in the repo directly but are used from the Gem. To make changes on these files, copy them from [here](https://github.com/mmistakes/minimal-mistakes) to the repo and Jekyll will prefer the local copy
- `academicicons.css` (contains Google Scholar icon) stylesheet included by adding it to `_includes/custom.html`
- Typography reverted back to older versions by adding stylesheets referencing fonts in `_includes/custom.html` and overriding SASS variables from `_sass/minimal-mistakes/_variables.scss` in `assets/css/main.scss` before `@import` statements (Instructions [here](https://mmistakes.github.io/minimal-mistakes/docs/stylesheets/))
- Changed font size and family of sidebar by overriding CSS statements from `_sass/minimal-mistakes/_sidebar.scss` in `assets/css/main.scss` after `@import` statements
