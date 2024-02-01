---
tags:
  - type/blogpost
created: 2024-01-30
---

# Mastering Aesthetics in Obsidian

![[Office1.png]]

Reading the wonderful post by PKM Beth, I wondered if the beautiful page layout she uses in Capacities could also be implemented using Obsidian. 

I analyzed the screenshots she presented and came to the following conclusion: The screen is divided in three major areas:
- A banner image
- A two column area with collapsable categories containing links to further information in the left and an image in the right column
- An area containing 12 cards which each one representing one century

The standard installation of Obsidian neither implements banners, nor multi-columns nor cards. But with one of the custom themes provided Obsidian and a few CSS snippets, a similar result as the one produced with Capacities can be achieved.



## Install the "banner-image.css" snippet

**TfT Hacker** has published a [CSS snippet for Obsidian]([Hacking Obsidian: Creating Notion-like banner images in Obsidian without Plugins | by TfTHacker | Obsidian Observer | Medium](https://medium.com/obsidian-observer/hacking-obsidian-creating-notion-like-banner-images-in-obsidian-without-plugins-7ad3e0bddc30), that creates Notion-like banner images without Plugins. I installed the snippet in the appropriate folder and enabled it under "Appearance/CSS snippets" in the Obsidian settings. I also increased the banner-height to 200px using the Style Settings plugin.

## Add "banner-position.css" snippet

If the image used for the banner is higher than the configured banner-height, the banner-image.css snippet always displays the center part of the banner file. Sometimes I want to display a part of the image above or below the center position. I therefore added a small snippet that allows to set the starting y-position of the image.

This can be done by using one of the y-positions predefined in the snipped. The value `py-0` sets the start position to the top of the image, `py-10`to 10% under the top, `py-20` to 20% and so on. Here is the CSS-snipped I implemented to achieve that:

```css
.banner-image img[alt*="py-0"] {
	object-position: center 0%;
}

.banner-image img[alt*="py-10"] {
	object-position: center 10%;
}

.banner-image img[alt*="py-20"] {
	object-position: center 20%;
}

.banner-image img[alt*="py-30"] {
	object-position: center 30%;
}

.banner-image img[alt*="py-40"] {
	object-position: center 40%;
}

.banner-image img[alt*="py-50"] {
	object-position: center 50%;
}

.banner-image img[alt*="py-60"] {
	object-position: center 60%;
}

.banner-image img[alt*="py-70"] {
	object-position: center 70%;
}

.banner-image img[alt*="py-80"] {
	object-position: center 80%;
}

.banner-image img[alt*="py-90"] {
	object-position: center 90%;
}
```

