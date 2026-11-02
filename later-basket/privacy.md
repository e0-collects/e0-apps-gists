# Privacy Policy

**Later Basket: Save Videos & Pages for Later, With a Note**
Effective date: November 2, 2026

Later Basket keeps a list of videos and pages you chose to come back to. This policy explains what data it handles.

## Summary
- Later Basket has no servers and no accounts. We do not collect, store, sell or share your data.
- There are no analytics, tracking or ads.
- Your basket stays in your browser.

## Data stored on your device
Saved with `chrome.storage.local` in your browser profile:
- each item you save: its address, title, channel or site, thumbnail, your note, when you saved it, and whether you opened
  it, finished it or set a reminder
- your settings
- your licence key, if you bought Pro

This data never leaves your device unless you download a backup file yourself. Removing the extension deletes it.

## Screenshots
When something you save has no picture, or its picture can't be fetched (a page behind a login, an image host that refuses), the
extension takes a small screenshot of what you saw: the card you pressed, or the top of the page. It's cropped to 320 by 180
pixels and stored on your device with the item, like any other thumbnail. It is never sent anywhere. Pages behind a login can
show personal details in that picture, so turn this off in Settings if you'd rather not keep them.

## What it reads on pages
- On YouTube, the extension runs on every page so it can show its button on video tiles. When you point at a tile it looks
  at that tile's link. When you press the button it reads the tile's title and channel.
- On other sites it reads a page only when you ask: when you click the toolbar icon, press the shortcut or choose it from
  the right-click menu. Then it reads the title, address, share image and selected text.
- If you turn on the button for every other site, Chrome asks for access to all sites and the same hover check runs on
  them. It looks only at the link under your pointer, and nothing is saved or sent until you press the button. Turning
  the setting off stops this right away. To withdraw the access itself, use the extension's details page in `chrome://extensions`.

## Requests it makes
Only these, each to do something you asked for:
- **YouTube** (`i.ytimg.com`, `www.youtube.com/oembed`): when you save a video, it fetches the thumbnail and, if needed, the
  title. These requests carry the video's ID.
- **The site hosting a picture**: when you save a link or page that has a picture, it fetches that picture to keep a small
  copy. If the site doesn't allow that, your basket page loads the picture from that site whenever the row is on screen.
  That site then sees an image request from your browser each time, so it could tell when you look at that row.
- **Gumroad** (`api.gumroad.com`): only if you enter a Pro licence key. The key is sent to check it when you activate, then
  about once a week. Gumroad handles the purchase under its own privacy policy, and we never see your payment details.

Your notes are never sent anywhere.

## Permissions
- **storage, unlimitedStorage:** keep your basket and its thumbnails on your device.
- **activeTab, scripting:** read the page you're saving, and show the note box, after you click.
- **contextMenus:** the right-click save options.
- **alarms, notifications:** Pro reminders.
- **favicon:** show a site's logo when an item has no picture.
- **Access to YouTube and i.ytimg.com:** show the button on video tiles, and fetch thumbnails.
- **Access to api.gumroad.com:** check a licence key.
- **Access to all sites (optional, off by default):** only if you turn on the button for every other site.

## Your notes and the page you're on
The note box is a separate frame belonging to the extension, not part of the web page. The page can't read what you type in it
or the note it shows. A page can tell the extension is installed, because it can see the empty element that holds the button and
can check for the frame's address.

## Contact
ezerocollective@gmail.com
