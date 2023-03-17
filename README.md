# The ICTD Wiki

You are currently viewing the ICTD Wiki's source code on GitHub. The ICTD Wiki is a fictional wiki used for as a creative writing exercise.

If you're looking for the wiki itself, you can find it at [ictd.wiki](https://ictd.wiki).

## Development

The wiki itself is split into two parts, the landing page and the wiki itself. The landing page is a static site built with simple HTML, CSS, and JavaScript. The wiki is an instance of [Gollum](https://github.com/gollum/gollum), a simple wiki engine built on top of [Git](https://git-scm.com/).

### Landing Page

Just edit the files in the `landing` directory and push to GitHub. This part of the site is hosted on [GitHub Pages](https://ictd-wiki.github.io/www/), using Caddy as a reverse proxy.

### Wiki

The wiki is a Gollum instance. To run it locally, you'll need to install Docker. Then, run the following command:

```bash
bin/dev
```

This will start a Docker container running the wiki. You can access it at [http://localhost:4567](http://localhost:4567).

Use the interface to edit the wiki. When you're done, commit your changes and push to GitHub.

The Wiki is hosted on a dedicated server running Caddy and Docker.
