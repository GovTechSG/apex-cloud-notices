# APEX Cloud User Doc Repository

This is a documentation repository for APEX Cloud, written for Documentation Portal, using [docsify](https://docsify.js.org/#/). You can find out what docsify or markdown extensions are supported [here](https://stg.docs.developer.gov.sg/docs/public/238425294/doc-portal-publisher-guide/#/).

> The repository is currently in active development and  contents will change rapidly.

## How to update

Copy the template markdown snippet from _template.md in the root folder and update your content accordingly. Newest content will be at the very top of the docs/home.md file so that it sorted by newest first.

Update the *Last updated* date in the same page when you are done.

## File Structure

All markdown files should live within the **/docs** folder. Each main section should be a separate markdown file by itself. If you have added a new main section, you should also update [_sidebar.md](docs/_sidebar.md) so that it will show up when the webpage is rendered.

All non-markdown files (i.e. images and sample code files) should live within the assets subfolder.

## Running Locally

### Setting Up

- Install docsify cli `npm -g install docsify-cli`
- Download this repository via `git clone`
- Run `docsify serve .`

### Syntax Highlighting

The repository has been pre-configured to pull in the default Developer Portal's styling for Documentations. (See [index.html](./index.html))

## Web Hosting

By default, once you commit and push any changes into github, the contents will be updated automatically. 

## Contributing

Please fork the repository, make your changes and submit a Pull Request.
