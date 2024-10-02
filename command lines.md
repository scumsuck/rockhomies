Running Eleventy

Execute this command in your terminal to run Eleventy: npx @11ty/eleventy

This will generate your .html files based on the files (such as templates) in your input directory. You have to execute this command after every change you make in your input folder. To preview your website, use the files in the output folder or the web server (see below).

You can also make Eleventy 'watch' your files for changes, so that you don't have to manually execute the command after every change:

    npx @11ty/eleventy --watch watches your files
    npx @11ty/eleventy --serve watches your files and starts a web server

If you do this, whenever you save a change, Eleventy will generate the html files anew. If you're using the web server (aka viewing your website at localhost, e.g. http://localhost:8080/) the page will even refresh for you automatically. 