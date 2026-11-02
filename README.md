# veil-site

The website for Veil, served at <https://veil.faustyu.xyz> by GitHub Pages.

It is one static page with no build step: `index.html`, the Archivo font in
`fonts/`, and the screenshots in `img/`. Pages publishes the root of `main`
as it is; `.nojekyll` turns Jekyll off and `CNAME` holds the custom domain.

To preview it, open `index.html` in a browser, or serve the folder:

```sh
python3 -m http.server 8000
```

The apps live in their own repositories:
[veil-macos](https://github.com/The-Veil-Foundation/veil-macos),
[veil-ios](https://github.com/The-Veil-Foundation/veil-ios),
[veil-desktop](https://github.com/The-Veil-Foundation/veil-desktop),
[veil-android](https://github.com/The-Veil-Foundation/veil-android).

The site was moved out of `veil-macos/docs`, with its history.
