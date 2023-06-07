# SWE-mkdocs
A small working example of a mkdocs site.

To get started, copy the whole site (or clone this repository) to a convenient place for development. You will need to install mkdocs - instructions are at https://www.mkdocs.org/user-guide/installation/. 

Now, from the command line or terminal, you can launch your site:

```sh
$ mkdocs serve
```

You will see the website in your browser at http://localhost:8000/.

## Where to start editing

Your main page is always the "index" file that generates the home page `index.html`. The source file is the one you edit, and it is in the `docs` folder. You will see that it is a **markdown** or `.md` file. MkDocs looks for markdown files to make your pages.

John Gruber is the originator of Markdown and his site contains [the documentation](https://daringfireball.net/projects/markdown/) you need to get writing very quickly.

You can use any plain tex editor to edit markdown files. I prefer [MacDown](https://macdown.uranusjr.com/) as a stand-alone editor for lone documents, or when I am making a collection, book or website, I use Microsoft's (yes, *Microsoft*) [Visual Studio Code](https://code.visualstudio.com/). It works very nicely as an editing environment and is in fact, a very powerful *Integrated Development Environment* or IDE.

As you make changes to your documents, mkdocs detects these when you save them and updates the site in your browser. Edit until you're ready to build the site.

## Build and deploy

Stop the mkdocs server by pressing `ctrl-c` in the terminal, and run:

```sh
$ mkdocs build
```

This will build the site and place the files in a new folder called `site`. This folder contains all of the files you need for your website; you should upload it to your server's home folder, often called the document root, and located at `/var/www/html/exmaple.com/public_html/`. Your ISP should tell you where to find it and how to upload files to your server.

If you cloned this repository, then you can adjust the settings in github to serve the content from the `site` directory.

## Try it!

I hope that's enough to get you started with your own site. Good luck!