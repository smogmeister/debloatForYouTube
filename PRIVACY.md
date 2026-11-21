# Debloat for YouTube: Privacy Policy

Last updated: 21 November 2026

Debloat for YouTube changes how YouTube and YouTube Studio look in your browser. It does not collect, store, sell or share any personal data, and it has no servers of its own.

## What the extension uses, and where it stays

**Your settings.** The on/off state of each switch in the popup is saved with Chrome's built-in extension storage (`chrome.storage.sync`). If you're signed in to Chrome, Chrome syncs these settings between your own browsers. The extension's developer can't see them.

**YouTube Studio data.** On YouTube Studio's analytics and Content pages, the extension reads the analytics already loaded for your channel. To fill in figures Studio doesn't show any more (such as dislikes or watch time over time), it requests them directly from YouTube Studio. These are read-only requests from your browser to `studio.youtube.com`, the same kind Studio makes itself. To make them, the extension uses YouTube's sign-in cookies in your browser to sign the request, as Studio's own page does. The cookies and the data never leave your browser except in that request to YouTube, and are never stored or sent anywhere else.

**YouTube pages.** On `www.youtube.com`, the extension hides page elements (Shorts, Playables, auto-dubbed videos) and adds a "Not interested" button. Clicking that button picks YouTube's own "Not interested" option for that video. Nothing is read from these pages beyond what's needed to find those elements.

## What the extension does not do

- It does not send data to the developer or to any third party.
- It does not use analytics, tracking or advertising.
- It does not load code from anywhere outside the extension.

## Permissions

- **storage**: to remember your switch settings.
- **studio.youtube.com**: to redesign Studio's analytics pages, show the likes column and hide Studio's AI features.
- **www.youtube.com**: to hide Shorts, Playables and auto-dubbed videos, and to add the "Not interested" button.

## Contact

Questions about this policy: hi.smogmeister@gmail.com
