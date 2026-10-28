# watch

A one-page video player. Open `?v=VIDEO_ID` to play that video in a
youtube-nocookie embed, full screen, nothing else on the page.

It exists because opening a `youtube-nocookie.com/embed/` URL directly sends no
`Referer` header, which YouTube rejects with "Error 153". Serving the embed from
a real page gives it an origin to check.

No tracking, no cookies, no analytics, no dependencies.
