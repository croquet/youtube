# Croquet YouTube Video Synchronizaer

## Introduction

Croquet YouTube app is a simple example of Croquet. A group of users can set a public YouTube video and then go to the same time code when one of the participants pause, play or choose a time from the slider.

## Code Organization

`app.js` contains the model and the view. `index.html` specifies elements and its styles. The visiblity of those elements are controlled by a few CSS classes.

You need to create a file called `apiKey.js` (by copying `apiKey.js-example`), and replace the value in it with your own Croquet api key from [Croquet Dev Portal](croquet.io/keys).

   ```JavaScript
   const apiKey = "<insert your apiKey from croquet.io/keys>";
   export default apiKey;
   ```

## Invoking Croquet YouTube

YouTube Video app does not require any build process. Just run an http server and open `index.html`.



