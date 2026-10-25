# Live on Stage — GigKit site template

The site template for **Live on Stage** (a project of The Tin Music and Arts), rendered
live by [GigKit](https://github.com/thatkevin/gigkit). Venue-owned template repo
for GigKit's "pull your template from a GitHub repo" feature (#686).

Edit the files and push — with the GigKit push webhook enabled, changes go live
automatically (GigKit fetches the pushed commit). Otherwise hit **Publish** in
the GigKit admin to pull the latest.

Styling: Tailwind via the Play CDN (self-contained; no build step). Jekyll-style
`_layouts` + page folders; dynamic content (events, news, …) is injected by
GigKit as `site.data.*`.
