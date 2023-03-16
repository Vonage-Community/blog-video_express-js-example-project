# Vonage Video Express basic demo

An example using the Vonage Video Express in a basic Vanilla JavaScript project. Make sure to view the accompanying [blog post](https://learn.vonage.com/blog/2021/09/23/video-express-is-here-and-why-it%E2%80%99s-awesome/) as well as the [documentation](https://tokbox.com/developer/video-express/).


## To get started

Open the `.env` file and replace **API_KEY** and **API_SECRET** with your own values found in your [Vonage Video API Dashboard](https://tokbox.com/account)

On the front-end,

- `views/index.html` is where all the parts of the application are laid out
- `public/script.js` is where the Video Express runs everything needed for the video chat demo.
- `public/style.css` and `public/style.css` are the styles for `views/index.html`

On the back-end,

- `server.js` creates the session that users will use to connect to the room. For applications with multiple rooms, the session IDs will need to be stored in a database.

## Deployed Demo

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/fork/github/Vonage-Community/blog-video_express-js-example_project/tree/StackBlitz)

