---
title: Welcome to Quartz
---

Quartz 4

    Authoring Content
    Building your Quartz
    Configuration
    Higher-Order Layout Components
    Hosting
    Layout
    Migrating from Quartz 3
    Philosophy of Quartz
    Quartz Showcase
    Setting up your GitHub repository
    Upgrading Quartz

Home

❯
Authoring Content
Authoring Content

Mar 04, 20262 min read

All of the content in your Quartz should go in the /content folder. The content for the home page of your Quartz lives in content/index.md. If you’ve setup Quartz already, this folder should already be initialized. Any Markdown in this folder will get processed by Quartz.

It is recommended that you use Obsidian as a way to edit and maintain your Quartz. It comes with a nice editor and graphical interface to preview, edit, and link your local files and attachments.

Got everything setup? Let’s build and preview your Quartz locally!
Syntax

As Quartz uses Markdown files as the main way of writing content, it fully supports Markdown syntax. By default, Quartz also ships with a few syntax extensions like Github Flavored Markdown (footnotes, strikethrough, tables, tasklists) and Obsidian Flavored Markdown (callouts, wikilinks).

Additionally, Quartz also allows you to specify additional metadata in your notes called frontmatter.
content/note.md

---
title: Example Title
draft: false
tags:
  - example-tag
---
 
The rest of your content lives here. You can use **Markdown** here :)

Some common frontmatter fields that are natively supported by Quartz:

    title: Title of the page. If it isn’t provided, Quartz will use the name of the file as the title.
    description: Description of the page used for link previews.
    permalink: A custom URL for the page that will remain constant even if the path to the file changes.
    aliases: Other names for this note. This is a list of strings.
    tags: Tags for this note.
    draft: Whether to publish the page or not. This is one way to make pages private in Quartz.
    date: A string representing the day the note was published. Normally uses YYYY-MM-DD format.

See Frontmatter for a complete list of frontmatter.
Syncing your Content

When your Quartz is at a point you’re happy with, you can save your changes to GitHub. First, make sure you’ve already setup your GitHub repository and then do npx quartz sync.
Customization

Frontmatter parsing for title, tags, aliases and cssclasses is a functionality of the Frontmatter plugin, date is handled by the CreatedModifiedDate plugin and description by the Description plugin. See the plugin pages for customization options.
Graph View

    Syntax
    Syncing your Content
    Customization

Backlinks

    Explorer
    Folder and Tag Listings
    Social Media Preview Cards
    Welcome to Quartz 4
    CreatedModifiedDate
    Description
    Frontmatter

Created with Quartz v4.5.2 © 2026

    GitHub
    Discord Community

Authoring Content



