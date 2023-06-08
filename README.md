# AI Frameworks Course Website Template with MkDocs

## Introduction

 This is a course website template created using `mkdocs`, a fast and simple documentation generator that builds static HTML pages from Markdown files. This template is designed for courses related to AI frameworks, and includes pages for the home, courses, schedule, evaluation, and a link to a GitHub repository.

## Installation

 To use this course website template, you need to have `mkdocs` installed on your system. If you don't have it installed, follow the instructions below:

## Installing `mkdocs`

 1. Open a terminal window or command prompt.
 2. Type `sudo pip install mkdocs` and press Enter
 3. Wait for `mkdocs` to download and install.

## Installing MkDocs Boostrap Theme

 1. Open a terminal window or command prompt.
 2. Type `pip install mkdocs-bootswatch` and press Enter
 3. Wait for `mkdocs-bootstrap` to download and install.

# Usage

 To use this course website template to create a new course website, follow these steps:

 1. Create a new repository on GitHub by clicking on the "New" button on your GitHub homepage.
 2. Give your repository a name and description, and select "Public" or "Private" as desired. Then, click on "Create repository".
 3. Download the template from this repository by clicking on the "Code" button and selecting "Download ZIP" or by running the following command in your terminal or command prompt:
 ```
 git clone https://github.com/yourusername/your-repository.git
 ```
 4. Extract the downloaded ZIP file or navigate into the cloned repository.
 5. Create a new directory for your course website and copy the contents of the extracted ZIP file or cloned repository into it.
 6. Navigate into your new course website directory.
 7. Preview your course website locally by running the following command in your terminal or command prompt:
 ```
 mkdocs serve
 ```
 8. This will start a local web server at `http://localhost:8000/` where you can view your course website in your web browser.
 9. Once you are happy with your course website, commit your changes and push them to GitHub using the following commands:
 ```
 git add .
 git commit -m "Initial commit"
 git push origin main
 ```
 10. Finally, deploy your course website to GitHub Pages by running the following command:
 ```
 mkdocs gh-deploy
 ```
 11. This will build your site and push it to the `gh-pages` branch of your repository. Your course website will be live at `https://yourusername.github.io/your-repository/` in a few minutes.

# Customization

 To customize this course website template, you can edit the `mkdocs.yml` file to add or remove pages, change the theme, and more. See the [MkDocs documentation](https://www.mkdocs.org/) for more information.

# Conclusion

 Creating a course website using `mkdocs` is a quick and easy way to share course content with students. With this template, you can get started quickly and easily, and customize the website to suit your needs.
