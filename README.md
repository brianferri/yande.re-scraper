# Yande.re image scraper

## ⛔ | Prerequisites

- [Node.js 16+](https://nodejs.org/en/download/) and npm ofc

## 🏃‍♂ | Installing and running the bot

### Instructions

 - Open a terminal instance in the script's working directory
 - run `npm i` or `npm install` to install the node dependency the bot needs to work
 - run the bot using `node yande.re.js <category> <--explicit? #ofPages>`
  - example: `node .\yande.re.js wet --explicit 10`

# Important Notes:
 - Each page will contain about 40 images
 - If you don't set the explicit tag then you will only download images which are considered "NSFW" or "Questionable".
  - And the contents may vary between 200 and 900 images.
 - Leaving the `#ofPages` blank for the `--explicit` tag will have the bot download as many images as the category has
  - Which can vary between 1 - 200k images :)
 - The bot WILL use AS MUCH CPU AS HUMANLY POSSIBLE. So make sure you close any program that you care about or are working on before running it.
 - Not setting the 
