# Personal Homepage

This is the source code for my personal homepage, hosted at [mikeshen.github.io](https://mikeshen.github.io). It is a fork of https://github.com/academicpages/academicpages.github.io. 

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## About

This repository contains the source code for my personal homepage. It includes information about my projects, blog posts, cv,  and more.

## Features

- Responsive design
- Blog posts
- SEO optimized
- Analytics integration

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/mikeshen/mikeshen.github.io.git
    cd mikeshen.github.io
    ```

2. **Install dependencies:**
    ```sh
    bundle install
    npm install
    ```

3. **Run the site locally:**
    ```sh
    bundle exec jekyll serve
    ```

4. Open your browser and navigate to `http://localhost:4000`.

## Usage

- **Adding a new post:** Create a new markdown file in the `_posts` directory following the naming convention `YYYY-MM-DD-title.md`.
- **Updating the site configuration:** Modify `_config.yml` for global settings and `_config.dev.yml` for development-specific settings.
- **Customizing styles:** Edit the SCSS files in the `_sass` directory.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.