---
layout: post
title:  "Initial Post - Setup Notes"
---

# Welcome 

This is the first post on the new site, using GitHub pages, where old content from a previous site (d8aism.com) is being migrated (slowly) over. 
 
# Site creation and content notes

Content migrated from previous storage is linked to one or more GitHub repositories and can be found by clicking on the menu or by using the search bar. 

Site creation depends on the installation of the following: xampp, Ruby, and Jekyll. Most markdown documents are created in R. The site uses the just-the-docs Jekyll theme, for its simplicity and powerful search capacity. Clicking on the search bar, I can find all of the ways I've described the parsing of JSON files, for example. 
 
Necessary files (Gem file, lock file, configuration file) were set up the first time the site was created locally (e.g., via the `bundle exec jekyll serve` command). The basic setup is pretty much to standard. One note: Webrick isn’t a bundled gem in standard libraries, so I added it as a dependency and re-ran the installation. 

# Directory Setup 

The following is my set-up, in case anyone else is looking for examples of how to make their own site. Note that in the `_layouts` folder, I don't have a **default.html**; my pages are rendered using the **home** layout. Contents are available for recycling on my GitHub page. 

```
\-- AMNakamura.github.io
    -- 404.html        # Default
    -- blog.html       # Contains the layout for posts 
    -- Gemfile         # Where Ruby Gems are listed 
    -- Gemfile.lock    # Detailed Gemfile, with versions of dependencies 
    -- GenData         # Folder created by me, containing the parent and child files for the menu bar
    -- index.markdown  # Home page
    -- myfavlinks.md   # Links
    -- _config.yml     # Lists the theme (just-the-docs) and other details
    -- _layouts        # One for posts, one for pages, one for about (just a page)
    |   -- about.html
    |   -- page.html
    |   \-- post.html
    -- _posts
    |   \-- 2022-08-20-FirstPost.md
    \-- _site           # The actual rendered site contents
        -- 2022        # Post folder for the year, contains subfolders for month and day
        -- 404.html    
        -- about.html
        -- assets
        -- blog.html  
        -- feed.xml
        -- GenData
        -- index.html
        \-- myfavlinks.html
```

