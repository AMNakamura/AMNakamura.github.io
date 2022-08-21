---
layout: post
title:  "Testing the first post on the new site"
---

# Welcome 

This is the first post on the new site, using GitHub pages, where old content from the previous site (d8aism.com) is being migrated (slowly) over. 
 
# Site creation and post set-up notes 

The source repository is named AMNakamura.github.io. Site creation depends on the installation of xampp, Ruby, and Jekyll. 
The _posts and other folders, plus necessary files (Gem file, lock file, configuration file) are set up the first time the site is created locally (e.g., via the `bundle exec jekyll serve` command). 

- Gemfile: where all of the Ruby Gems are listed. You can modify the Gemfile that Jekyll created, in Notepad
- Gemfile.lock: More detailed version of Gemfile. The specific versions of dependencies defined in Gemfile are recorded here.
    - Webrick isn’t a bundled gem in standard libraries, so add it as a dependency, using the `gem add "webrick"` command. Then, delete Gemfile.lock and rebuild it with a `bundle install` command.

Post file names follow a date-slug.md naming convention (YYYY-MM-DD-PostName.md). 

The site uses the just-the-docs Jekyll theme, for its simplicity and powerful search capacity. Clicking on the search bar, I can find all of the ways I've described the parsing of JSON files, for example. 