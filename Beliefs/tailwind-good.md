---
title: Tailwind is good
draftDate: 01 Dec 2025
---

The fact that people defend the esoteric idea of separating styles and markup always baffles me. Like yeah, you don’t want to send a massive dump of crap in 1998, and CSS is a nice enough way to extract out a design system yet keep things small. But come on its `$CURRENT_YEAR`. IMO DiasyUI is basically the logical conclusion of how far you can take a CSS design system, while being as ergonomic as possible. But it is what is: a hack. And if you want to extend every possible minor variation as it’s own semantic variant class defined in some god-forsaken stylesheet, please go for it. But I will be using utility classes bc it’s the closest thing we have to sanity in web styling.

And yes you could make a number of small classes by yourself to augment these one-offs. But what do you get when you keep pushing down that road? A worse version of tailwind that you had to make yourself bc you’re too stubborn to just use it.

If an analogue to the `style` attribute was created that was as performant and extensible as CSS, and there was a bombproof implementation of properly composable markup tags to replace what we could consider a “class”, I have no doubt it would be lauded as a great improvement. Like it or not, CSS-in-JS is popular for a reason, despite the fact that it is a MASSIVE hack and very complex.
