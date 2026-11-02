# Two editions

- `index.html` is the master and the **full** edition. Edit only this file.
- `lite/index.html` is generated: run `python3 build.py` after every change to the master.
- The build stops if a lite change no longer matches the master, so the lite edition never silently keeps a full-edition feature.
- Both editions: unlisted, blocked for search engines, behind the preview access code.
- The `full` / `lite` pill next to the logo switches edition on the same screen with the same profile. It is a demo tool and must be removed from the lite edition before any public release.
