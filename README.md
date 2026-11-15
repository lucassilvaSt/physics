# Lucas's physics portfolio

Live at **https://lucassilvast.github.io/physics**. When you push changes to GitHub, the site updates by itself within about a minute.

## What to edit

| To change… | Edit this file |
|---|---|
| The intro on the home page | `index.md` |
| Your photo | Replace `assets/images/bio-photo.png` with a square photo, keeping the same file name |
| The text under your name, or add your email | `_config.yml`, in the `author:` section |
| Awards | `_data/awards.yml` |
| Projects | One file per project in `_projects/` |

## Adding a project

1. Copy `_projects/example-project.md` and rename the copy, e.g. `_projects/coil-gun.md`. Use lowercase letters and dashes, no spaces.
2. Put the project's images in `assets/images/`.
3. Fill in the fields at the top of the file (title, excerpt, image…) and write the page below the second `---`.
4. Set `featured: true` on your best 2–3 projects so they also show on the home page.
5. Delete `example-project.md` once you have a real project.

## Adding an award

Open `_data/awards.yml`, copy one of the example blocks, and change the text. Keep the same indentation (two spaces); YAML is picky about it.

## Previewing before you push (optional)

With Ruby installed, run this once in this folder:

    bundle install

Then, each time you want to preview:

    bundle exec jekyll serve

and open http://localhost:4000/physics/.

Built on the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) Jekyll theme.
