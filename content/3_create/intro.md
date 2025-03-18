# Creating Engaging Content 

**Jupyter Book** allows for the integration of various markup languages and formats, including Markdown files, Jupyter notebooks, MyST Markdown notebooks, reStructured Text, and more.

## Goals

This chapter aims to include the following goals.

1. Learn which types of files you can integrate into your Jupyter Book course.
2. Learn how to create new files.
3. Learn how to format your text with Markdown.
4. Learn how to embedd images, videos, and slides.
5. Learn how to include feedback questions.
6. Learn how to set up an online repository (your course).

MyST is a markup language that draws inspiration from RMarkdown and is fully integrated for use with Jupyter Book. It allows for more advanced formatting options and the ability to include interactive elements, such as widgets and code snippets, within your content. Jupyter Book is able to parse MyST in both .ipybn and .md files, allowing for flexible content creation.

Here, we present only a short overview of the features of MyST. However, there is much more documentation on [the MyST website.](https://myst-parser.readthedocs.io/en/latest/syntax/syntax.html#syntax-core)

## First things first

Open up Visual Studio Code (or Jupyter Lab if you prefer using that). Create a new file by clicking on "File" and then on "New File." Here, you can choose which file format you want to choose. Choose .iypbn for interactive Files or create a new one.md (Markdown) file in the folder for your project.

### .iypbn vs .md - When should we use what?

````{tab} .ipynb
`.ipynb` files are Jupyter Notebook files and are primarily used for interactive data science and scientific computing. They allow for the combination of code, text, and visualizations all in one place, making it easy to document and share code-driven projects. They are often used by data scientists and researchers to share their work with others and can be easily converted to other formats like .html or .pdf for sharing.

**.ipynb files are best for interactive, code-driven projects**
````
````{tab} .md (Markdown)
 `.md` files are Markdown files, which are primarily used for creating simple, easy-to-read documents. They use a simple syntax for formatting text and are often used for documentation, READMEs, and other types of text-based content. They are also commonly used in conjunction with version control systems like Git and can be easily rendered on various platforms.

 **.md files are best for documentation, READMEs, and other types of text-based content**
````


