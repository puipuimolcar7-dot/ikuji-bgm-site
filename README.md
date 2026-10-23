# 育児BGMナビ site

Support / privacy pages for the 育児BGMナビ app, and `tracks.json`, the video list the app downloads on launch
(same schema as `app/content/tracks.json` in the app repo). To swap a video that stopped working, edit
`tracks.json`, bump `updatedAt`, and push; apps pick it up on their next launch.
