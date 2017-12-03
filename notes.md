# Jekyll Notes
-------------

## Getting Started

To create a new jekyll site at path
> jekyll new <PATH>

To create a new jekyll site in the current directory that you are in
> jekyll new .

Pass the --force option if the current directory is not empty

By default, the Jekyll site is installed with Minima theme. The folder structure of the theme is hidden from you,
To create Jekyll site without any theme use,
> jekyll new myblog --blank

For any help 
> jekyll new --help

## Build

To generate current folder into ./site
> jekyll build

To generate current folder into <destination>
> jekyll build --destination <destination>

To generate <source> folder into <destination>
> jekyll build --source <source> --destination <destination>

To generate current folder into ./site and watch for changes, and regenerate automatically
> jekyll build --watch

### NOTE
Desitnation folders are cleaned, by default, when the site is built. Files not created by your site will also be cleaned. To keep the files that you have created in <destination>, you need to specify such files in <keep_files> configuration directive.

## Serve

To start the local built in development server at http://localhost:4000/.
Auto-regeneration is enabled by default. Use --no-watch to disable.
> jekyll serve

To serve from <destination>
> jekyll serve --destination <destination>

## Directory Structure

Jekyll sites directory structure -  From [Jekyll Documentation](https://jekyllrb.com/docs/structure/)

[Screenshot](https://screenshots.firefox.com/Hw16R9QKpzUyqkko/jekyllrb.com)
