# Tick: install on your iPhone

Tick is a web app. You put these files on a free host once, then add Tick to your Home Screen. After that it opens full-screen like a normal app and works offline.

## 1. Put it online (free, about 5 minutes, works from the iPhone)

**GitHub Pages**

1. Sign up at github.com, or sign in.
2. Tap **+ → New repository**. Name it `tick`, set it to **Public**, and tap **Create**.
3. Tap **uploading an existing file**. Unzip `tick-app.zip` in the Files app, then select **all 8 files** at once. There are no folders.
4. Tap **Commit changes**.
5. Open the repo's **Settings → Pages**. Under *Branch*, choose `main` and `/ (root)`, then tap **Save**.
6. After about a minute your app is live at `https://<your-username>.github.io/tick/`.

On a computer, **Netlify Drop** (app.netlify.com/drop) is faster: drag the unzipped folder onto the page.

## 2. Install it

Open the link in **Safari**, tap **Share ⬆︎ → Add to Home Screen → Add**. From then on, open Tick from its icon.

## 3. Connect Apple Calendar & Reminders

In Tick, go to **☰ → Settings & Apple apps → One-time setup**. The guide there walks you through three shortcuts in the Shortcuts app:

| Shortcut | What it does |
|---|---|
| `Tick Reminders` | Turns a task into an Apple Reminder that alerts you on time |
| `Tick Calendar` | Adds a task to Apple Calendar as an event |
| `Tick Import` | Copies your next 14 days of Calendar events into Tick |

The names must match exactly.

## Good to know

- Your data is stored **on this iPhone only**. Use **Settings → Save backup file** now and then.
- Opening Tick from the icon and opening it in Safari give you separate copies of your data. Always use the icon.
- To update the app later, upload new files and change `VERSION` in `sw.js` (e.g. `tick-v2`). Then close Tick and open it again.
