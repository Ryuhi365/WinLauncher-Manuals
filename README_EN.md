# WinLauncher Standard

Start every Windows workday from `Alt+Space`.

WinLauncher Standard is a practical Windows launcher for opening the files, folders, web pages, OneNote pages, SharePoint sites, shared folders and reusable text you use every day.

Launcher cuts down on hunting and opening.

Snippets cuts down on retyping, pasting and remembering.

## Your first ten minutes
You do not need to organise everything up front.

Start by registering just three things you use every day.

A good first three:

- A file you open every morning
- A shared folder or web page you use often
- A piece of text you paste often

After that, add things as you notice them: whenever you catch yourself hunting for the same thing, or typing the same sentence again.

## What is in the ZIP
The ZIP is a single file that works in both Japanese and English. There is no separate download per language.

- `WinLauncher.exe`
- `README_FIRST.txt`
- `ChangeLog.md`
- `en` folder — `README.md` / `LICENSE.txt` / `WinLauncher_Manual_EN.pdf` / `sample`
- `ja` folder — the same set in Japanese

The `en\sample` folder holds sample CSV files that show what is worth registering. They are not loaded automatically. Read them for ideas and add items by hand, or try `Import CSV` — in that case rewrite the paths, URLs and wording for your own environment first.

## Getting started
1. Extract the ZIP anywhere you like.
2. Run `WinLauncher.exe`. There is no installer, and you do not need to install .NET.
3. Press `Alt+Space` to show WinLauncher.
4. Register three things you use every day: a file, a shared folder, a piece of text.

## Changing the display language
Right-click the WinLauncher icon in the notification area and choose `日本語` or `English` from `Language / 言語`.

Exit and restart WinLauncher to apply the change. Your choice is saved and kept for the next launch. On first run the app follows your Windows display language.

## System requirements
- Windows 10 or Windows 11, 64-bit
- An internet connection is needed only for features that open a web page or run a web search

Notes:

- Windows SmartScreen or your security software may warn you on first launch.
- If you use this on a work computer, follow your organisation's rules.

## Getting into the habit

### Step 1: Register the places you go every day
The Excel file you open every morning, the shared folder, the SharePoint page for your project, the OneNote notebook for your work. One is enough to start.

### Step 2: Open them from `Alt+Space`
Instead of navigating in Explorer or hunting through browser bookmarks, call WinLauncher up and open the item from there.

### Step 3: Save the text you keep rewriting
Email replies, chat messages, work-log templates, form text, checklists. Anything you write more than once.

Snippets is not only for code.

### Step 4: Let it grow
WinLauncher suits growing a list alongside your actual work better than building a perfect shelf on day one.

## What you can register
Anything that opens as a URL, and anything Windows can open as a path, can go in the Launcher.

| Kind | Examples |
| --- | --- |
| Web page | ChatGPT, YouTube, Amazon, an intranet portal |
| Teams | A channel, a group chat, a meeting link |
| Microsoft 365 | Outlook on the web, Microsoft 365, a SharePoint page |
| File | Excel, PowerPoint, PDF, Word, OneNote |
| Folder | A local folder, a shared folder |
| WebDAV folder | A SharePoint folder you can open in Explorer |

## What it does

### Open the places you use, fast
Register the files, folders, web pages, OneNote pages, SharePoint sites and shared folders you use every day, then call them up from `Alt+Space`.

### Search what you registered
Filter your items by name or by tag. A tag like "expense" or "quarterly" is enough — you do not need to remember the exact filename.

### Reuse text
Save email replies, chat messages, enquiry responses, work logs, form templates, checklists and code as Snippets. Search for one and copy it to the clipboard when you need it.

### Search modes
Type `/` at the start or the end of the search box and a list of modes appears. Both `/mode keyword` and `keyword /mode` work, so when a normal search does not find what you want, you can just append a mode at the end.

| Mode | What it searches |
| --- | --- |
| `/Everything` | Files on this PC, through Everything (voidtools) |
| `/Edge` | Your Microsoft Edge bookmarks |
| `/Search` | Pick a destination such as Google AI, Amazon or Rakuten |
| `/ConvSPLink` | Converts a SharePoint UNC path to a URL and back |
| `/Recent` | Recently used files, as recorded by Windows |
| `/Snippet` | Your saved Snippets |
| `/DropDest` | The destination folders used by the Drops window |

`/Everything` needs Everything (voidtools) installed and running. It is not required — without it, only that one mode returns no results, and everything else works as normal.

### Drops
A small window beside the Launcher with two drop targets:

- **Convert to PDF (ppt/word)** — drop PowerPoint or Word files to write PDFs into the same folder. This needs PowerPoint or Word installed.
- **Copy to a registered folder** — drop files or folders to copy them into a folder you registered with `/DropDest`. You can rename them on the way. You can also drop an Outlook mail attachment straight onto the tile.

### Tasks
A light task list that sits beside the Launcher. It is hidden on first run; press `Alt+Shift+3` to show it, and the setting is remembered.

It is deliberately small: no notifications, no repeating tasks, no team sharing, no cloud sync. If you need a real task manager, use a real task manager.

### CSV import and export
Launcher items and Snippets can both be exported to CSV and imported back.

### A few conveniences
- `Alt+K` sets a colour marker per Kind (or per Type in Snippets)
- `Alt+R` cycles the sort order
- `Alt+Z` scales the whole app to 130%
- `Alt+S` runs a Google search on whatever is in the search box

## Who this suits
- You use Excel, OneNote, SharePoint and shared folders every day.
- You spend real time hunting for files and pages you already know about.
- You have sentences you type again and again in email, chat or forms.
- You keep looking up where a bookmark or a shared folder lives.
- You want each day to get slightly lighter, not fully automated.
- Windows on its own does not give you a good enough path through your work.

## Who this does not suit
- You want everything automated.
- You want cloud sync or multi-device sync.
- You need central management or controlled deployment for an organisation.
- You want the same experience on Mac or on a phone.

## Keyboard basics

### Calling it up
- `Alt+Space` — show WinLauncher
- `Esc` — hide

### Launcher
- `Ctrl+Enter` — open the selected item
- `Alt+Shift+Space` — register whatever is selected in Explorer or another app
- `Alt+N` — add by hand
- `Alt+V` — add the URL or path on the clipboard
- `Alt+Enter` — edit
- `Alt+Delete` — delete
- `Alt+C` — copy the path or URL
- `Alt+O` — open the parent folder
- `Alt+R` — change the sort order
- `Alt+S` — Google search

### Snippets
- `Alt+2` — go to Snippets
- `Ctrl+Enter` — copy the selected Snippet
- `Alt+N` — add
- `Alt+V` — add from the clipboard
- `Alt+Enter` — edit
- `Alt+Delete` — delete

### Side windows
- `Alt+Shift+3` — show or hide Tasks
- `Alt+Shift+4` — show or hide Drops

The full shortcut list is always visible at the bottom of the window. A chip with a darker border has a tooltip; hover it for the details.

## Sample files
The `en\sample` folder holds fictional sample CSV files.

- `en\sample\Launcher_Sample_EN.csv`
- `en\sample\Snippets_Sample_EN.csv`
- `en\sample\README_EN.txt`

Notes:

- They are not loaded automatically.
- Common URLs are filed as `Browser`, folders as `Dir`, Office files as `Excel` / `PowerPoint` / `PDF` / `OneNote`, and Teams channels and group chats as `Teams`.
- The Snippets samples include email replies, chat messages, meeting notes, work logs, SQL and Power Query.
- The fictional file paths will not open as they are. Rewrite them for your own PC or workplace.
- If you try `Import CSV`, the rows are merged into your existing data. Back up first if that matters.

## Where your data is stored
Everything is stored locally under `%LocalAppData%\WinLauncher`. No cloud account is required.

- Launcher — `commands.json`
- Snippets — `snippets.json`
- Launcher run log — `launcher_runlog.json`
- Kind colours — `kind-colors.json`
- Snippet Type colours — `snippet-type-colors.json`
- Drop destinations — `drop-destinations.json`
- Tasks — `Tasks.json`
- Tasks / Drops window visibility — `task-window-mode.json` / `drop-window-mode.json`
- Display language — `ui-language.txt`

## Backing up
Back up your registered data regularly.

At minimum:

- `%LocalAppData%\WinLauncher\commands.json`
- `%LocalAppData%\WinLauncher\snippets.json`

If you use them:

- `%LocalAppData%\WinLauncher\kind-colors.json`
- `%LocalAppData%\WinLauncher\snippet-type-colors.json`
- `%LocalAppData%\WinLauncher\drop-destinations.json`
- `%LocalAppData%\WinLauncher\Tasks.json`

## Updating
Exit WinLauncher and back up your data before updating.

1. Exit WinLauncher.
2. Back up the files you need from `%LocalAppData%\WinLauncher`.
3. Replace `WinLauncher.exe` with the new one.
4. Start it and check that your registered items are still there.

## Please note
- WinLauncher is a Windows application built by an independent developer.
- If you use it on a work computer, follow your organisation's rules.
- Security software or an organisation policy may restrict or block it.
- SmartScreen and similar warnings may appear.
- Managing and backing up your own work data remains your responsibility.
- Cloud sync and multi-device sync are not provided.
- Because this is downloadable software, all sales are final. Please check the requirements, the notes and the support scope before you buy.

## Licence and redistribution
- One purchase covers one user (for a gift, the recipient).
- Personal and business use are both permitted.
- Sharing, redistributing, reselling, sub-licensing, lending, uploading, reposting, mirroring, bundling or transferring the app, the ZIP, the manual, the sample files or the download link to a third party is prohibited.
- Please buy one copy per user.
- See `en\LICENSE.txt` for the full text.

Copyright © 2026 Ryuhi. All rights reserved.

## Support

### What is covered
- Guidance on basic use
- Guidance on installing and updating
- Sharing known issues
- Fixing defects where practical

### What is not covered
- Deployment help tailored to a specific company environment
- Changes to your organisation's security settings
- Any guarantee of recovering work data
- Custom development
- Central management features for organisations

### Getting in touch
For payment and purchase questions, follow the guidance on the store you bought from.

For questions about using WinLauncher, or to report a problem, use the contact details on the product page.

If you cannot retrieve a file you have paid for, or the file you downloaded is damaged, contact us. We will restore your download or supply a working file. That is not a refund.

## FAQ

### What is this app?
A practical Windows launcher that calls up the files, folders, web pages, OneNote pages, SharePoint sites, shared folders and reusable text you use every day, from `Alt+Space`.

### What should I register first?
A file you open every morning, a shared folder you use often, and a piece of text you paste often. Three is enough to start.

### Is Snippets only for code?
No. Email replies, chat messages, work notes, form templates and checklists all work well.

### Does it index my PC?
Not by itself. WinLauncher shows what you registered. If you install Everything (voidtools) and use `/Everything`, that mode searches your files through Everything — but it is optional, and the rest of the app does not depend on it.

### Do I need an internet connection?
The core features work locally. You need a connection only for features that open a web page or run a web search.

### Can I use it on a work computer?
That depends on your organisation's rules and security settings. Check before you install it.

### Is this a subscription?
No. It is a one-time purchase.

### Can I sync across several PCs?
No. Cloud sync and multi-device sync are not provided.

### Can I register Teams and SharePoint links?
Yes, as long as they open as a URL — Teams channels, group chats, meeting links and SharePoint pages all work. SharePoint folders that Explorer can open over WebDAV can be registered too. Whether a registered link actually opens depends on your company's Microsoft 365 setup.

### Can I back up my data?
Yes. Back up the JSON files under `%LocalAppData%\WinLauncher`.
