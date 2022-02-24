# bye-bye-vod

## Set up instructions

* login to `https://members.equinoxplus.com/`
* check your `localStorage` object for a key with the beginning of `@@auth0`. extract `body.refresh_token` from that object 
* paste the value of `refresh_token` into the `equinox-token.json` file
* install [ffmpeg](https://www.ffmpeg.org/) and [youtube-dl](https://youtube-dl.org/)
* run `node index.js`


## Notes

You will need to figure out for yourself if you want to filter the list of videos based on instructor
