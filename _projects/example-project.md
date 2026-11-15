---
# ─────────────────────────────────────────────────────────────────────────────
# EXAMPLE PROJECT: copy this file for each new project.
# 1. Copy it in the _projects folder and rename it, e.g. "coil-gun.md"
#    (lowercase, dashes instead of spaces). The file name becomes the page's link:
#    lucassilvast.github.io/physics/projects/coil-gun/
# 2. Fill in the fields below, then replace the text under the --- line.
# 3. Delete this example file once you have a real project.
# ─────────────────────────────────────────────────────────────────────────────

title: "Example Project: [title of project]"

# One or two sentences shown on the project card.
excerpt: "I built XXX with XXXX and measured XXXX."

# Where/when it happened, shown in small italics on the card.
context: "Independent project · Summer 2025"

# Tools, parts, or methods you used.
tools: "Skill1 • Python • Skill2, etc."

# The picture on the card. Put the image in assets/images/ and write its path here.
header:
  teaser: /assets/images/placeholder.png

# featured: true puts this project on the home page too. Pick your best 2–3.
featured: true

# Lower numbers are listed first.
order: 1

# Optional buttons on the card. Delete any you don't have.
links:
  - label: "Code"
    url: "https://github.com/lucassilvaST"
  # - label: "Video"
    url:
---

<!-- Everything below is the project page itself. Write it like you're explaining it to a curious friend. -->

## The question

What did you want to find out or build, and why did it interest you? One short paragraph.

## How I did it

Describe your setup and method. A photo of the setup helps a lot. Also if you did a simulation, put like code excerpt or table of parameters you can control.

![A photo of my setup]({{ '/assets/images/placeholder.png' | relative_url }})

## Results

What did you measure or make work? Plot, video, etc.

<!-- To embed a YouTube video, put this on its own line, using the ID from the video's link (the part after `v=`): -->
<!-- `{% raw %}{% include video id="YOUR_VIDEO_ID" provider="youtube" %}{% endraw %}` -->

## What went wrong (and how I fixed it)

The things that didn't work the first time, and what you changed. [This is often the most interesting part to read.]

## What I learned

The physics you understood better, and what you'd try next.
