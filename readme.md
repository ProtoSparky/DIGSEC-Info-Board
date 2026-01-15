# Readme
This project is written using markdown and Mkdocs

## Requiremnts
* Mkdocs
* mkdocs-material
* mkdocs-git-revision-date-localized-plugin
All of these can be installed with pip, so make sure python is installed on your pc. 

## Adding or editing
Use the terminal and ``mkdocs serve`` within this directory to get a development preview on ``http://127.0.0.1:8000`` of the code you've edited. 
The webserver has to be restarted for changes to apply, and if doing so, yields no changes, i suggest you turn off your browser cache  by ticking "Disable cache" in the network tab of inspect element. 

### Useful links
[Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/)
[MKdocs Getting started guide](https://www.mkdocs.org/getting-started/)

## Deploying your code
To deploy your code to github pages, make sure you have push access to ``DIGSEC-Info-Board`` AND ``ProtoSparky.github.io``. Make sure both of these repos are in the same root directory, push your changes to ``DIGSEC-Info-Board``, and run the commands below to push the compiled site to the public. 

``cd ../ProtoSparky.github.io/``

``mkdocs gh-deploy --config-file ../DIGSEC-Info-Board/mkdocs.yml --remote-branch master``