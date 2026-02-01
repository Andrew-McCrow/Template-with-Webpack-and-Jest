## SET UP INSTRUCTIONS

# Clone Repo
- Create new repo in Github using template
- Clone repo locally in VS code: git clone git@github.com:Andrew-McCrow/XXX.git


# Webpack
- install webpack (create node_modules directory):
npm install --save-dev webpack webpack-cli
- run webpack (create dist directory):
npx webpack
- handle html, CSS and Images:
npm install --save-dev html-webpack-plugin
npm install --save-dev style-loader css-loader
npm install --save-dev html-loader
- set up local server:
npm install --save-dev webpack-dev-server
- run local server (http://localhost:8080/):
npx webpack serve


# Jest
- Install Jest:
npm install --save-dev jest
- Run Jest
npm test -- --watch
