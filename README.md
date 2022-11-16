![](https://www.nasa.gov/sites/default/files/thumbnails/image/nasa-logo-web-rgb.png=100x)

# NASA APOD API Picture of the day

in this application you can look at the picture of the day from NASA by simply entering a past date. The picture with the title and the description is already visible. This is my first project with an API and of course it had to be NASA.

## Build tools :hammer:

- HTML
- SCSS
- JavaScript
- Node
- Express
- Webpack
- [APOD API](https://github.com/nasa/apod-api)
- Workbox

## Installation :on:

Check if node and npm are installed.

`npm -v`
`node -v`
I use Node v14 for this project.

Move to the project folder

`cd <yourprojectFolder>`

Clone the repo

`git clone <reponame>`

Install with npm

`npm install`

Install loaders and plugins

Choose the installation for your development mode

`npm i -D @babel/core @babel/preset-env babel-loader`
`npm i -D style-loader node-sass css-loader sass-loader`
`npm i -D clean-webpack-plugin`
`npm i -D html-webpack-plugin`
`npm i -D mini-css-extract-plugin`
`npm i -D optimize-css-assets-webpack-plugin terser-webpack-plugin`

Go to the [APOD API](https://api.nasa.gov/) and get your personal API Key.

Configurate your environment files and using dotenv

`npm install dotenv`

Create a `.env` file and don't forget to add them to the `.gitignore` file.
Fill the `.env` file with your API KEY for example:

`API_KEY=***********************`

now you can build the project with

`npm run build-dev` or `npm run build-prod`

after that you can start it

`npm start`

Open your browser at http://localhost:8081
