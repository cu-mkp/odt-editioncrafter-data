# odt-editioncrafter-data
Data and metadata for an edition created with EditionCrafter for Ornament : Design : Translation by Tianna Uchacz

## Generating EditionCrafter Data

EditionCrafter has an accompanying command line interface (CLI) that is used to generate the artifacts it displays. This software is written in Javascript, so you will need to have Node.js installed on your computer. Once Node.js is installed, run the following command to install the tool:

`npm install -g @cu-mkp/editioncrafter-cli`

For this project, use the following command from the base directory to generate the artifacts:

`editioncrafter process texts/caryatidum.xml texts https://cu-mkp.github.io/odt-editioncrafter-data/texts`

Replacing caryatidum.xml with the name of the XML you wish to update. Once these changes are commited to the main branch of this repo, they will be published by GitHub Pages and available for EditionCrafter to render on your website.

See the Getting Started guide on the EditionCrafter homepage for more information.