# Open Textbook Guide

## What this is

A small website that helps Columbia College faculty choose open textbooks (open educational resources, or OER). The goals are to save students money and, where licenses allow, to let faculty use the materials with AI.

The site offers faculty two paths:

- **Adopt:** use a good open textbook as it is.
- **Remix:** combine chapters from two or three open textbooks, with AI help, into a better fit for the course.

The live version is at https://jkoxford-a11y.github.io/Open-Textbook-Guide/. Jon Oxford (Psychology) maintains it. This folder is a working copy, and editing it does not change the live site.

## Files

- `index.html`: start page (why open textbooks, adopt vs. remix).
- `repositories.html`: "Where to look," the main open textbook collections and what each offers.
- `licenses.html`: Creative Commons licenses, what each allows, which can be combined, and how to give credit.
- `shared.css`: styles for every page. Keep it in the same folder as the pages.

## How to work here

- **Plain HTML and CSS only.** There is no build step, framework, or JavaScript library. Keep it that way so anyone can open and edit the files.
- **Preview** by opening an `.html` file in a web browser and refreshing after each change.
- **Reuse the existing styles** in `shared.css` (for example `card`, `tag`, `paths`, `glossary`, `tablewrap`, `pullquote`) before adding new ones. Put new styles in `shared.css`, not inside a page.
- **Each page carries its own navigation bar** at the top. If you add, rename, or remove a page, update the nav on every page and mark the current page with `class="current"`.
- **Keep the voice:** short, plain sentences written for busy faculty. Say things directly.
- **Update the "Draft as of" date** in a page's footer when you change that page.

## Accuracy rules

- **Never state a book's or collection's license without checking it on the source's own website.** Licenses change. For example, OpenStax moved all its books to CC BY-NC-SA 4.0.
- Counts (number of books, modules, and so on) change often. Re-check them before changing them, and keep the "checked on [date]" note on `repositories.html` current.
- If you're unsure about a fact, ask the person you're working with instead of guessing.

## Sending changes back

When the edits are done, send the changed files back to Jon Oxford. He'll merge them and publish them to the live site. List what you changed and why so the changes are easy to review.
