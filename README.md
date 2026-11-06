# parthalab.github.io
Repo for Parthalab

Below are descriptions of each section of the website that can be modified/customized; within code, green comments are more detailed descriptions on the editable options.

## Homepage 
- hero with carousel
- locations section with maps
- featured project section
- get involved section with a button that jumps to "positions" page


## Research
- customizable photos (all stored in static/images/research/)
- featured current study
- partners listed at the bottom


## Publications
This page has three components: html, js, json files.
Html: acts as the monitor
Json: updatable catalog of all the publications
js: connects the two files to order and filter the papers

To add/delete/modify a tag:
1. go to .js file
2. edit topic tags list
3. id = id name used in .json file; label = readable name shown on the website filter buttons

To add a paper:
1. copy newest entry
2. paste above newest entry
3. edit according to prompt
4. if pdf avaialble: add to static folder. route to "static/pdf/pdf name"
5. if pubmed avaialble: add to pubmed section
6. if website available: add to wwww section

## news
News is divided into four sections: Lab News, Press Releases and Media Coverage, Awards, and a Photo Gallery.
Lab news and Awards has their own pages to maintain.
Press is simply a list.
Still working on the photo gallery...


## Positions
- email listed on webpage
