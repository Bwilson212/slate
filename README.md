# insurtech-api

## Dependencies

Minimally, you will need the following:

* [Ruby](https://www.ruby-lang.org/en/) >= 2.5
* [Bundler](https://bundler.io/)
* [NodeJS](https://nodejs.org/en/)
* [Git](https://git-scm.com/)

Z Shell preferably

Please note, only Linux and macOS are officially supported at this time. While slate should work on Windows, it is unsupported.


## Running slate

You can run slate in two ways, either as a server process for development, or just build html files.

To do the first option, run:

```bash
bundle exec middleman server
```

and you should see your docs at http://localhost:4567.

The second option (building html files), run:

```bash
bundle exec middleman build
```

## Files to edit

If you cloned from this repo then everything you need to know is in the source folder. 

To add a new language go into source folder and then open `index.html.md.erb`. Must be one of https://git.io/vQNgJ

To add errors, go to source/includes/_errors.md.

Adding a new section to the slate is pretty simple. Create a new folder in the api/[version]. Inside this folder you will create a _[version].html.md.erb file. Here you will link your sections. 

To add Markdown Syntax view [external link](https://github.com/slatedocs/slate/wiki/Markdown-Syntax)
