---
title: Site Todo
description: A work in progress.
draftDate: 3000-12-31
---
# Weblog Post Ideas
- [ ] Supabase studio as a standalone Postgres GUI
- [ ] Guitar hero drums to midi
- [ ] Pocket operator sync
- [ ] Blogging with Astro and Obsidian
# Formatting, etc
- [ ] Bottom margin following checklists
- [ ] Block quotes
- [ ] Links to other obsidian blog posts
	- [ ] This format (This is an alt title)[[the-dilettantes-garden]] should render with the alt title and link to the post
	- [ ] This format [[the-dilettantes-garden]] should render with the post title and link to the post
- [ ] Indented lists
# Misc
- [ ] Pre-load fonts

Example from [fontsource](https://fontsource.org/docs/getting-started/preload)

```typescript
import '@fontsource-variable/open-sans';
import openSansWoff2 from '@fontsource-variable/open-sans/files/open-sans-latin-wght-normal.woff2?url';

<link rel="preload" as="font" type="font/woff2" href={openSansWoff2} crossorigin="anonymous" />
```

- [ ] More fun facts
- [ ] Dynamic fun facts?
	- Extract them into a yml/json/text file for easy mobile editing?
	- Maybe a markdown file so I can edit in obsidian? In theory the whole file can be just top matter?
- [ ] Collage page with simple dynamic rendering of external images
	- I’m imagining like a table full of Polaroids?   
- [x] Pic of me n beans on Home Screen
- [ ] Break out the “beliefs” sections into separate posts with a “belief” tag, reconstitute them into the beliefs post as a special type of post?
- [ ] Look into using [uniorg](https://github.com/rasendubi/uniorg) for live org-mode parsing
	- Once this happens, I can probably just move away from MDX and rely entirely on server-side org mode parsing
	- Publish a formal org-mode astro.js package?
	- Would maybe be nice for TODO stuff as well (like this doc)
- [ ] Opengraph site banner
- [ ] Opengraph blog heroes
- [ ] Backlinks? Not sure if I really even want it, but could be a fun footnote
- [ ] Some format which can be replaced by a dynamic value
	- Something like:
	- `#(stravaMilesRidden)`
	- Which would replace the content with some runtime-calculated variable
	- Need to run the blog in SSR mode and figure out if it’s even possible to do this in a post-processed markdown page
	- Maybe just configure all MD files in obsidian to be treated as MDX
- [ ] Default `updatedDate` to be the file change date
	- A manually applied `updatedDate` would take precedence
- [ ] Visitor counter
	- Likely just via an analytics service I set up like Matomo or GoatCounter