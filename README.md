# PiStudio libraries and help — update site

PiStudio reads `manifest.json` here at start-up (and on Settings → Libraries & help → Check for
updates) and downloads any library that is newer than the one it has:

- `machines.pistudio-pack` — the machine library (lasers by type, make and model)
- `rotaries.pistudio-pack` — the rotary library (PiBurn and other rotaries, gear ratios, pictures)
- `help.pistudio-pack` — the help

**Do not edit these files by hand.** They are generated from the `content/` folder of the PiStudio
repository by `publish-content.cmd` (`tools/content/publish.mjs --upload`), which checks them and
pushes here. Served by GitHub Pages at https://lensdigital.github.io/pistudio-content/.

© LensDigital
