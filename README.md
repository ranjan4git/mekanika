This repo contains the files used to create the website for Mekanika, the Mechanical Engineering UG students society. 

The URL is www.mekanika.iitkgp.ac.in

These files were initiated by Jeevan.

The way I am going about creating the files is as follows:

* First, I write the markdown files (.md)

* Using pandoc, I convert the .md files to .html files. The style file used is style.css

* The command I use is: `pandoc -s index.md -c style.css -o index.html`
