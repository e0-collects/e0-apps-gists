# Privacy Policy

**Stand-in: Hide Your Name When You Record**
Effective date: October 14, 2026

Stand-in is a browser extension that swaps words you choose (such as your name or email address) for stand-ins on web
pages, so you can record or share your screen without showing them. This policy explains what data it handles.

## Summary
- Stand-in has no servers. We do not collect, store, sell or share your data.
- Stand-in makes no network requests. There are no analytics, tracking or ads.
- Everything stays in Chrome on your computer.

## Data stored on your device
Your settings are saved with `chrome.storage.local` in your Chrome profile:
- the words you want to hide, and what to show instead
- whether to hide email addresses, and the placeholder to use
- the CSS selectors to blur
- the sites to use it on, whether pages stay blank until masked, and whether Stand-in is on

This data never leaves your computer. Removing the extension deletes it.

## Page content
To swap your words before a page is drawn, Stand-in reads the text of the pages you open, inside your browser. It
changes only what is displayed. It never stores, copies or sends page content, and it never changes text you type
into forms or editors.

A small helper runs in each page to notice when the page builds new parts of its layout (shadow DOM). It signals
Stand-in with an event that carries no data.

While Stand-in is on, a website could detect that it is installed and, by showing text and checking whether it
changes, work out which words you are swapping. Stand-in starts switched off, shows "ON" on its icon while it works,
and can be limited to the sites you choose, so you can keep it off everywhere else.

## Permissions
- `storage`: saves your settings on your computer.
- Content scripts on all sites: needed to swap your words on any page you choose to record.

## Children
Stand-in is not directed at children and collects no personal information from anyone.

## Changes
If this policy changes, the new version will be posted with the extension and its effective date updated.

## Contact
email at ezerocollective@gmail.com
