---
title: SSR 2
description: Test
draftDate: 2025-12-28
mdx: true
---

import Avatar from '../../components/RandomAvatar.astro';

Blah blah blah blah

<Avatar server:defer class="h-16 w-16">
  <div slot="fallback" class="bg-background h-16 w-16"></div>
</Avatar>

Blahhhhhhhhhhhh blah blah blah

<Avatar class="h-16 w-16" />

Blah blah blah
