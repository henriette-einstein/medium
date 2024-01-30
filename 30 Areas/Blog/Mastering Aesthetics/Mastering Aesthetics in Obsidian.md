---
tags:
  - type/blogpost
created: 2024-01-30
---

# Mastering Aesthetics in Obsidian

Reading the wonderful post by PKM Beth
## Install the "banner-image.css" snippet

**TfT Hacker** has published a [CSS snippet for Obsidian]([Hacking Obsidian: Creating Notion-like banner images in Obsidian without Plugins | by TfTHacker | Obsidian Observer | Medium](https://medium.com/obsidian-observer/hacking-obsidian-creating-notion-like-banner-images-in-obsidian-without-plugins-7ad3e0bddc30), that creates Notion-like banner images without Plugins. I installed the snippet in the appropriate folder and enabled it under "Appearance/CSS snippets" in the Obsidian settings. I also increased the banner-height to 200px using the Style Settings plugin.

## Add "banner-position.css" snippet

If the image used for the banner is higher than the configured banner-height, the banner-image.css snippet always displays the center part of the banner file. Sometimes I want to display a part of the image above or below the center position. I therefore added a small snippet that allows to set the starting y-position of the image.

This can be done by using one of the y-positions predefined in the snipped. The value `py-0` sets the start position to the top of the image, `py-10`to 10% under the top, `py-20` to 20% and so on.
