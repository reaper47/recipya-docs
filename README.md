# Recipya's Documentation Website

This repository contains all the source files for the documentation website of [Recipya](https://github.com/reaper47/recipya). 
The documentation is designed to provide a comprehensive guide for users and developers to understand, use, and contribute to the project.

## Available Languages

The documentation is available in the following languages:
- English (default)
- French

You can switch between languages using the language selector on the website at the bottom left. 

## Contributing

Please feel free to contribute to translating the documentation into other languages or to improve this project in any way possible.

### Dependencies

You will need to install [Hugo (extended version)](https://gohugo.io/installation/) to build the project.

### Building the Project

Follow these steps to build the project yourself:
1. Clone the project.
   ```bash
   git clone https://github.com/reaper47/recipya-docs.git
   ```
2. Build the docs.
   ```bash
   hugo server -D
   ```
3. View the docs at `http://localhost:1313/`.

Alternatively, you may use the [development container](https://recipes.musicavis.ca/guide/docs/development/devcontainer/).
Recipya's Docker [container](https://github.com/reaper47/recipya/tree/main/.devcontainer) includes all the necessary tools and dependencies 
you need to start writing code quickly.

### Examples

#### Fixing a typo

Let's say you want to fix a typo in the English version of the docs on the [Docker page](https://recipya-docs.musicavis.ca/docs/installation/docker/). 
You would:
1. Click the "Edit this page on GitHub →" button in the sidebar on the right.
2. Amend the page.
3. Commit and open a pull request.

#### Adding a language

Let's say you want to translate the documentation to Japanese. 
You would:
1. Clone the repository.
2. Under the `content` folder, copy-paste a language folder, e.g. `en`.
3. Rename it to `jp`.
4. Translate
5. Once done, commit and open a pull request.
