# Project Template Repository

This repository serves as a template for new projects, providing a pre-configured environment with all necessary dependencies and webpack configuration.

## Features

- Pre-installed dependencies
- Webpack configuration
  - Separate production and development configurations
  - Loaders for images in all files
  - Loaders for fonts
  - Webpack Dev Server for rapid development
- Premade npm scripts

## Getting Started

1. Click the "Use this template" button at the top of this repository and select "Create a new repository".
2. Clone your new repository to your local machine:
```
git clone https://github.com/your-username/your-new-repo.git
```
3. Navigate to the project directory:
```
cd your-new-repo
```
4. Install the dependencies:
```
npm install
```

## Usage

### npm scripts

This template comes with some pre-configured npm scripts to streamline your development process:

- ```npm run test```: Placeholder for running tests (currently not implemented)
- ```npm run build```: Builds the project for production using webpack.prod.js
- ```npm run dev```: Starts the webpack dev server for development using webpack.dev.js
- ```npm run deploy```: Deploys the dist folder to GitHub Pages

## Deployment

This template includes a script for easy deployment to GitHub Pages. To deploy your project:

1. Make sure your project is built and up to date:
```
npm run build
```
2. Run the deploy script:
```
npm run deploy
```
This will push the contents of your ```dist``` folder to a ```gh-pages branch``` in your repository, which can be configured to serve your GitHub Pages site.

