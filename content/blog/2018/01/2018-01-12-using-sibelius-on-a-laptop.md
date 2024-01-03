---
title: "Using Sibelius on a Laptop"
date: "2018-01-12"
categories: 
  - "music-education"
  - "projects"
  - "technology"
tags: 
  - "notation-software"
  - "resources"
  - "sibelius"
---

In my opinion, Sibelius has some decent and intuitive keyboard shortcuts on a full keyboard, with its heavy emphasis around the numpad.  However, I find it to be essentially unusable on a Macbook Pro which lacks the numpad.  It _has_ a “notebook" shortcut set, but I find that to be just as unusable, and far from intuitive.

I find it important to be able to enter into Sibelius very quickly.  I don’t use a MIDI keyboard input, and in all apps I try to minimize my use of the mouse.  As such, I’ve customized my keyboard shortcuts in Sibelius and I think they’re worth sharing.  Not just do I think they make Sibelius truly usable on my Macbook Pro, but I think they’re good enough that they could be faster for desktop users than moving their hands back and forth between the numpad.

You can download my shortcuts [here](https://www.dropbox.com/s/49jqht0zj490kem/Ehler%27s%20Sibelius%20improved%20laptop%20shortcuts.sfs?dl=0).  To install them, you simply need to add them to your keyboard shortcut directory.  On OSX, this is located at:

~/Library/Application Support/Avid/Sibelius/Keyboard Shortcuts

You can open Finder, press ⇧⌘G, and paste the above path into Finder to load the folder open.  Here’s a video describing the process:

\[youtube https://www.youtube.com/watch?v=QM19IbYcF28?rel=0\]

It’s worth noting that I don’t know if this shortcut file is usable on Windows because of the difference in modifier keys.  If someone would like to take my shortcuts and make an approximation for Windows, I’d be happy to link to it in this post.

I made this before I thought it would be worth sharing, as such, I didn’t document every change from the default. Feel free to share in the comments anything that’s different that I don’t mention. Maybe there’s a way to compare my shortcut file with the default with a script.

The biggest change is how I rebound the numpad.  As in Avid’s keyboard shortcuts, 1–9 on the numpad are mapped to 1–9 on the top row of the keyboard.  The top row (on Apple’s default keyboard, the characters =,/, and \*, which cover the accent, staccato, and tenuto on the first page of the keypad) are bound to ⇧-, ⇧=, and ⇧⌫ on the number row.  The numpad “enter” is rebound to \\ (which does ties on the first page of the keypad) between return and delete on the regular keyboard.  The forward and backward keypad buttons (+ and - on Apple’s numpad) are rebound to = and - without shift on the number row.  This lets you use the entire keypad without moving your fingers from the home row.

Other, less significant differences that I’m aware of:

- ⌥⇧+2–9 are add below
- ⇧, is advance caret (from when I was trying Dorico)
- ⇧. activates the “Dot Undot Rhythms” plug-in (also inspired by my Dorico trial)
- ⇧0 is bar rest
- ⌥M triggers marcato accents.
- Accidental parentheses is ⌥P (this is just a shortcut to the “bracket accidental” action on the accidentals keypad, and is subject to the same finicky behavior there)
- Some rebinding done in the “Moving” options
- I had ⌘P as export>pdf actually because I almost never physically printed directly from a dialog during my undergrad. It’s not the case in this file, but it might be useful for others.

There are some shortcuts that are worth noting that I’m unsure if I changed:

- ⌥F is fermata
- ⌥O is Optimize Staff Spacing
- I might have moved other things around under Layout shortcuts
- ⇧N is stop playback
- ⌥⇧H toggles the selected “invisibles” in the View pane from showing or note showing.

The following bindings are open and might be useful if there’s something you really want bound that I don’t have bound: ⌥+0, ⌥+1, ⌘+1, ⌘+0

It’s worth noting I don’t have the following actions keybound:

- Beaming – none of the actions on the third keypad are bound, I just change over to it
- Breath marks – Individual symbols can’t be bound in Sibelius, but I think I’m going to use the [Scoring Notes’ breath line workaround](https://www.scoringnotes.com/tutorials/better-breath-marks-sibelius/) down the road.  Lines can be keybound and I think custom lines can be as well.
- Barlines – I don’t see a way to bind a shortcut to just open the barlines pane (like you can the time signatures, etc.), and no single barline type is worth binding to me, but it might be to you.

Shortcomings:

- When you’re entering in text, you can normally use a number of shortcuts to put in symbols (like ⌘4 for a quarter note in the text).  I believe these shortcuts only work with the numpad numbers, and I can’t find a way around this.  Would love to hear otherwise in the comments.  See below
- I don’t know that it’s possible to do tab notation with the default keyboard shortcuts without a numpad.  My shortcuts don’t fix this and I don’t know that there’s a way to do that.

I do all of my work in Sibelius without using my MIDI keyboard.  The three main advantages of using one to me are:

- Pre-selecting your octave instead of changing it after inputting the note (and thus hearing only the note you intend)
- Putting in chords all at once
- Velocity for playback

I am not so bothered by the first or third points for it to be a consideration, and I work primarily on wind parts, and the second part is fairly moot unless you’re editing primarily for piano parts.  To me, the speed of doing everything so fluidly without moving your hands from the computer keyboard makes this set-up more viable than using a MIDI keyboard.

Here’s a video demonstrating these keyboard shortcuts in action.  This video is primarily aimed at just demonstrating workflows in Sibelius for students to get a better handle on the software, but hopefully it demonstrates the speed at which you can work in Sibelius with these shortcuts.

\[youtube https://www.youtube.com/watch?v=1H2jnj5cx1M?rel=0\]

\[youtube https://www.youtube.com/watch?v=yuVboyT8V\_E\]

_Edit 1/26/18:_  
I’ve discovered that you can customize the shortcuts for inserting special text.  I have miraculously ignored the Word Menu options under Preferences since I bought Sibelius.  It’s worth noting that there is nothing visually distinguishing about the way it’s bound by default and the way it needs to be bound for use on the number row (both say, for example, on a quarter note ⌘4).  You also need to change them in each category, the most important for note values being “Tempo Words.”  
  
I have modified this on the upload of my keyboard shortcuts I have posted, _however I do not know if this is stored in that file._  You may need to fix this yourself.  Please let me know one way or the other whether this is remedied by my shortcuts file if you try it.  If it’s not working, try setting [this file](https://www.dropbox.com/s/s6lx61897l47b0s/Word%20menus.swm?dl=0) in:

~/Library/Application Support/Avid/Sibelius/Word Menus
