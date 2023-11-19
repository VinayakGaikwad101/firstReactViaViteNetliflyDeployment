# How to make and deploy a react project in netlify via vite
## my site is live at: https://firstreactappviavite.netlify.app/

## Note: always prefer vite docs for deployment over this README.md: https://vitejs.dev/guide/

# First, we make a react app via vite
# Below are the steps to do the same:

## Step 1) make a folder where you want to make a react app

## Step 2) open the folder in vs code (or any text/code editor), and make sure to install latest version of node.

## Step 3) open the terminal and type the following:

## Step 4) npm create vite@latest

## Step 5) type the project name

## Step 6) Select React as framework

## Step 7) JavaScript

## Step 8) now follow the instructions that are stated on the terminal, they'll be as follows:
cd yourProjectName
npm install (this step takes some time)
npm run dev (open the url in the browser to run the project locally)
## Note: to close the server, press Ctrl+C on windows.

## Step 9) make the necessary changes (make sure to include all assets[images/audio/png/jpeg/etc] in the public folder, and other HTML, CSS, js, jsx files in src folder.


# Next we deploy it to netlify using the netlify cli:

## Step 1) to build the project for deployment/production, run the following in the terminal after closing the server:
npm run build
## Step 2) to check how the project will look after deployment, run:
npm run preview
again, close the server after checking that it runs perfectly
## Step 3) create netlify account, then run:
npm install -g netlify-cli
## Note: this needs to be done only once per device
## Step 4) in the terminal, and if it asks for authorization, do so:
ntl init
then, select: Yes, create and deploy site manually
enter team name
enter site name
## Step 5) run the following(make sure you are in correct folder):
ntl deploy
if it asks for a folder, type public
## Step 6) run the following:
netlify deploy --prod
if it asks for folder, type dist

it will generate a website url, that is our site's url that can be shared.
here is my site's url:  https://firstreactappviavite.netlify.app/

