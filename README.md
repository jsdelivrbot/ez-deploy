# ez-deploy

## Quick Start
1. Clone this repo
    ``` sh
    git clone https://github.com/godhand1607/ez-deploy.git
    ```
2. Go into the project's root directory
3. Run `npm install`
4. Run `npm start`
5. On your browser, access http://localhost:8080/

## Deployment platforms
1. Easiest -- surge.sh
    ```
    surge -p dist
    ```
2. Easier -- gh-pages
    ```
    git subtree push --prefix dist origin gh-pages

    OR

    npm run deploy
    ```
3. Easy -- AWS S3
    ```
    s3-website create <bucket-name>
    s3-website deploy dist
    ```
