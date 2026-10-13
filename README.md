# endpaperdev.github.io

Endpaper's studio site and press kits, served by GitHub Pages at https://endpaperdev.github.io/

```
index.html                 studio page: games, press contact
assets/                    capsules and the Endpaper mark used by the studio page
the-infinite-library/      press kit (self-contained: index.html, images/, videos/)
faultfinder/               press kit (self-contained)
_old-repo-redirect/        NOT served here. Copy this index.html into the old
                           endpaperdev/the-infinite-library-presskit repo so the
                           July URL redirects to the new location.
```

Adding a game: make a folder named after the game's URL slug with its own
`index.html`, `images/` and `videos/`, then add a card to `index.html` at the root.
No build step. `.nojekyll` stops GitHub running Jekyll over the folders.

Keep every file under 100 MB (GitHub's hard limit) and the repo under 1 GB.
