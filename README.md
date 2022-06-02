# Yande.re image scraper

## ⛔ | Prerequisites
 
- [Node.js 16+](https://nodejs.org/en/download/) and npm ofc
- If you're on Windows you will need to download [wget](https://eternallybored.org/misc/wget/) - latest version
  - You will need to place the `wget.exe` in `C:\Windows\System32`

## 🏃‍♂ | Installing and running the bot

### Instructions

 - Open a terminal instance in the script's working directory
 - run `npm i` or `npm install` to install the node dependency the bot needs to work
 - run the bot using `node yande.re.js <category> <--explicit? #ofPages>`
   - example: `node .\yande.re.js wet --explicit 10`

# Important Notes:
 - Each page will contain about 40 images
 - If you don't set the explicit tag then you will only download images which are considered "Safe" or "Questionable".
   - And the contents may vary between 200 and 900 images.
 - Leaving the `#ofPages` blank for the `--explicit` tag will have the bot download as many images as the category has
   - Which can vary between 1 - 200k images :)
 - The bot WILL use AS MUCH CPU AS HUMANLY POSSIBLE. So make sure you close any program that you care about or are working on before running it.

<h1 align="center"><img src="./2022-05-25_08-13-04.gif" width="1080px"></h1>
