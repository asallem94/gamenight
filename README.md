# Game Night

Public website for Game Night, the organization that connects people through multiplayer games. Double Agent and Monster Mania 360 each have their own about, privacy, and content rights pages.

The site is static HTML and CSS. There is nothing to install and no build step.

## Run locally

From this folder:

```bash
python3 -m http.server 8000
```

Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

Run that command inside `gamenight`, so the server’s root is this folder. Stop the server with Ctrl+C.

Opening `index.html` as a file will not follow the page links correctly. Use the local server above.

## Pages

| Page | Path |
| --- | --- |
| Home | `/` |
| Double Agent about | `/doubleagent/about/` |
| Double Agent privacy | `/doubleagent/privacy/` |
| Double Agent content rights | `/doubleagent/content/` |
| Monster Mania 360 about | `/monstermania/about/` |
| Monster Mania 360 privacy | `/monstermania/privacy/` |
| Monster Mania 360 content rights | `/monstermania/content/` |

Published copies of these pages are at [https://asallem94.github.io/gamenight/](https://asallem94.github.io/gamenight/).

For App Store Connect, use that game’s privacy URL under App Privacy → Privacy Policy URL, and that game’s content URL under App Information → Content Rights.
