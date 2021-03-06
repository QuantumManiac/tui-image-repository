# tui-image-repository

A fun little image repository app with some interesting twists: 
- Everything (including picture viewing) is in the terminal
- All images are stored as a base64 string in a Sqlite database

Features:
- User authentication
- Add images to repo from file or URL
- Rudimentary full-text searching that goes through image titles and descriptions
- View counts for images 

## Requirements

Created on NodeJS v14.15.5

## Usage
```
npm i 
node index.js
```
You will be prompted to log in or register. Register a new account and you will be good to go.

A few sample images have been provided that you can either search for or use the "random images" feature in "search images" to browse.

Create new images and see how that workflow goes.

## Testing
Testing is somewhat lacking due to time constraints and complexity (the test cases have been described but not implemented), but can be run with:

```
npm run test
```
