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
Html: acts as the container
Json: updatable catalog of all the publications
{
  "publications": [
    {
      "year": 2025,
      "authors": "Lastname, F., Lastname, F., & Parthasarathy, A.",
      "title": "Title of the first sample paper goes here.",
      "venue": "Journal Name, 00(0), 000-000.",
      "tags": ["aging", "evoked-potentials"],
      "links": {
        "pdf": "https://example.com/replace-with-pdf-link.pdf",
        "pubmed": "https://pubmed.ncbi.nlm.nih.gov/00000000/",
        "www": "https://doi.org/replace-with-doi"
      }
    },
    {
      "year": 2024,
      "authors": "Lastname, F., & Parthasarathy, A.",
      "title": "Title of the second sample paper goes here.",
      "venue": "bioRxiv. Preprint.",
      "preprint": true,
      "tags": ["speech-in-noise", "synaptopathy"],
      "links": { "www": "https://doi.org/replace-with-doi" }
    }
  ]
}


## news
News is divided into four sections: Lab News, Press Releases and Media Coverage, Awards, and a Photo Gallery.
Lab news and Awards has their own pages to maintain.
Press is simply a list.
Still working on the photo gallery...


## Positions
- email listed on webpage
