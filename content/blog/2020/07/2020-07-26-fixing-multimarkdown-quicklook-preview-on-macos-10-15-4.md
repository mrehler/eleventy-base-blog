---
title: "Fixing MultiMarkdown QuickLook Preview on macOS 10.15.4"
date: "2020-07-26"
categories: 
  - "technology"
---

I’ve made great use out of a [QuickLook from Fletcher Penny](https://multimarkdown.com/download/#freeutilities) to preview Markdown files (which I use a lot of). Without this, you’re previewing the raw Markdown which is still readable, but usually I find this lending clarity to whatever I’m trying to preview over the plain text.

Unfortunately, with macOS Catalina 10.15.4, I’ve been unable to use it. The day I updated, it started rejecting the quicklook generator because it couldn’t verify the developer. It took a bit of digging, but I found a solution on the GitHub page for an unrelated project (that is also a QuickLook generator). There might be a ‘better’ way of doing this by the book (building it yourself in Xcode, etc.) that is a bit beyond me, but this worked for me.

From [this link](https://github.com/whomwah/qlstephen#permissions-quarantine)

> # Permissions (Quarantine)
> 
> If you run into issues with macOS not letting you run the plugin because it’s not signed by a verified developer you can follow these steps:
> 
> 1. Install the plugin using one of the methods above
> 2. run `xattr -cr ~/Library/QuickLook/MultiMarkdownQuickLook.qlgenerator` (sudo if needed)
> 3. run `qlmanage -r`
> 4. run `qlmanage -r cache`
> 5. Restart Finder by…
>     - Restarting your computer
>     - or holding down the option key and right click on Finder’s dock icon, then select “Relaunch” from the menu

(I just tweaked the path in those directions so it actually points at `MultiMarkdownQuicklook.qlgenerator` instead. It might also be titled `MultiMarkdown QuickLook.qlgenerator` or be in `/Library/QuickLook/` instead of `~/Library/QuickLook` if you grabbed a similar utility from someone other than Fletcher Penny.
