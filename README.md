# FRC Docs

A new project aiming to improve documentation for the [*FIRST* Robotics Competition](http://www.firstinspires.org/robotics/frc).

This site uses the [Edition theme](https://github.com/CloudCannon/edition-jekyll-template) for Jekyll.

## Develop

Edition was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

### Documentation pages

* Add, update or remove a documentation page in the *Documentation* collection.
* Change the category of a documentation page to move it to another section in the navigation.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.

### Change log

* Add, update or remove change log entries from your posts.
* Tag entries as minor or major in the front matter.

### Search

* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

### Navigation

* Change `site.show_full_navigation` to control all or only the current navigation group being open.
