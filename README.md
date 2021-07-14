# Filter Test

This repository was created as a way to test the features of the [face-api.js](https://justadudewhohacks.github.io/face-api.js/docs/index.html) library and to determine the viability of using it to create minimal real time image filters in the style of Snapchat filters. Ultimately, the test was a success and the code will likely go on to see more usage in that project.

I will be leaving this repository public so that others looking for usage examples can find it. face-api.js and all the accosiated models belong to their original creators, their inclusion here is simply because I need them to run.

It should also be noted that if you plan on testing this you will more than likely need a reverse proxy that handles SSL for you. I use [NGROK](https://ngrok.com/) for testing and [a pretty sweet NGINX Docker solution](https://github.com/evertramos/nginx-proxy-automation) for production, but you can roll your own solution if you see fit.
