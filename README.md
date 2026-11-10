# Karthik Kumar Allenki

This repository contains the personal website published at
[allenkikarthik.github.io](https://allenkikarthik.github.io/). Recruiters and
hiring teams can get in touch through the LinkedIn link on the site.

The site is a static, responsive page. A GitHub Actions workflow deploys the
repository to GitHub Pages on every push to `main`, including changes to
`index.html` and other site files.

## Enable deployment

In the repository's **Settings → Pages**, set the build and deployment source
to **GitHub Actions**. After that one-time setup, push changes to `main` and
the workflow will publish the site. You can also run the workflow manually
from the repository's **Actions** tab.

## Local preview

Open `index.html` in a browser, or start a local static server from the
repository root:

```sh
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

Karthik
