# How to change the text on the website

All the words on the website are in one file: **index.html**. Open it in a plain text editor, such as Notepad on Windows or TextEdit on Mac. Don't use Word, because it can break the file.

## Where each text is

The page has four parts. Each part starts with a label line that looks like this: `<!-- Footer -->`. These lines don't show on the website. They're only there to help you find your way. From top to bottom:

1. **Top of the page: name and contact buttons**: the big headline, the sentence under it, and the two buttons.
2. **What we do and prices**: the short description and the price list.
3. **Bring your bike in: opening hours and contact**: the opening hours, the phone number and the email address.
4. **Footer**: the small line at the very bottom of the page.

To find a text quickly, press **Ctrl+F** (on a Mac, **Cmd+F**) and type a few words of it.

## How to change a text

Every line has two kinds of content:

- **Words the visitor sees.** These are always between a `>` and a `<`.
- **Instructions for the browser** (the program people use to view websites). These are everything inside the pointed brackets `< >`.

**Only change the words between `>` and `<`.** For example, to change a price:

```
<span class="price">€69</span>
```

Change only `€69`, for example to `€75`. Leave everything else exactly as it is.

**The phone number and email address appear twice**, once at the top and once in "Bring your bike in". Change both places.

## Never touch

- **styles.css**: this file controls how the page looks.
- **Anything inside `< >`**, including the pointed brackets themselves.
- **The names of the files in the images folder** (the folder that holds the photos).
- **The fonts folder**: the lettering styles the page uses.

## How to swap a photo

The photos are in the **images** folder:

- **workshop.jpg**: the photo at the top of the page
- **detail.jpg**: the photo next to the price list
- **shop-front.jpg**: not shown on the page right now

To replace a photo, give your new photo **exactly the same name**, including the `.jpg` at the end. Then put it in the images folder in place of the old one. A wide photo works best.

If you'd rather keep your photo's own name, or the new photo shows something different, don't change anything yourself. Send me the photo, tell me where it should go, and I'll make the change.

## How to undo a mistake

- **Before you start:** make a copy of index.html and keep it somewhere safe, for example as `index-backup.html` on your desktop.
- **While you're editing:** press **Ctrl+Z** (on a Mac, **Cmd+Z**) to undo your last change. Press it again to go back further.
- **If the page looks broken after saving:** replace index.html with your copy. Then try your change again, or send it to me.

After each change, save the file and open index.html in your browser to check how the page looks.
