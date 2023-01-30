# webpack-seed
A simple webpack seed for static HTML sites with SCSS.

## Getting Started
1. Clone the repository: https://github.com/nerkat/webpack-seed.git
2. Install dependencies: npm install
3. Start the development server: npm run start
4. Build for production: npm run build
## File Structure


    ```properties
    webpack-seed/
    ├── src/
    │   ├── index.html
    │   └── script/
    │   │   └── index.js
    │   │   └── comps/
    │   └── style/
    │   │   └── index.scss
    │   │   └── base/
    │   │   └── comps/
    │   └── assets/
    │       └── fonts/
    │       └── images/
    │           └── favicon/
    └── webpack.config.js

    ```

## Scripts 
* npm start: Runs the development server
* npm run watch: Runs webpack in development mode with watch mode on
* npm run build: Runs webpack in production mode
* npm run test: No tests specified
## Dependencies
* clean-webpack-plugin
* css-loader
* file-loader
* mini-css-extract-plugin
* sass
* sass-loader
* webpack-dev-server
* Dev Dependencies
* html-loader
* html-webpack-plugin
* image-webpack-loader
* webpack
* webpack-cli
* License
* This project is licensed under the ISC License.

## Bugs
Report bugs at https://github.com/nerkat/webpack-seed/issues.