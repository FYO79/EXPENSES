# My Year — expenses & kids' education

A one-page app that replaces the two Excel files **My Year** and **Kids' Education**.
The school year runs **1 September → 31 August**. It runs on your MacBook in Safari (or any browser) and keeps working offline.

## What's inside

| Page | What it does (same idea as the Excel file) |
|---|---|
| **Month** | Salary, other income, **From last month** (money left over last month, added automatically) and the expense log. Spent / Left fill in by themselves. |
| **Where the money went** | On the Month and Year pages: every category you spent on, biggest first, with the amount and its share (%). |
| **Year** | Fills in by itself: expenses by item × 12 months, income, expenses, saved, "the year in short", and a small chart. |
| **Kids** | Log payments per kid: School fees, Private lessons, Books. Summary table kid × month with totals. |
| **Settings** | Backup file, CSV for Excel, categories, kids, currency. |

### Fill once → it appears in the other months
- **Salary is entered every month.** The app starts empty; each month keeps only what you type in that month.
- **Repeat every month.** When adding an expense or a kids' payment, tick *Repeat every month* and pick *until* (default: August). It is added on the same day of each month. When you edit or delete one of them you can choose *only this month* or *this and the following months*.
- **Kids and Month are connected both ways.** On the Month page, choose *School fees* and pick the kid, or *Private lessons* and pick the kid and Private lessons / Books — it also appears on the Kids page. A payment logged on the Kids page also appears in that month's expenses. Editing or deleting it in one place changes both.

## Put it on GitHub (GitHub Pages)

1. Sign in to github.com → **New repository** → name it e.g. `my-year` → **Private** or Public → *Create*.
   (GitHub Pages on a *private* repo needs a paid plan. On a free plan use a Public repo — that's fine: **your numbers are never in the repo**, only the empty app. Your data stays on your MacBook.)
2. **Add file → Upload files** → drop all the files: `index.html`, `manifest.webmanifest`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `favicon-32.png`, `favicon.ico`, `README.md` → *Commit changes*.
3. **Settings → Pages** → *Source: Deploy from a branch* → Branch `main`, folder `/ (root)` → *Save*.
4. After a minute the address appears, like `https://YOUR-NAME.github.io/my-year/`.
5. On your MacBook open that address in Safari → **File → Add to Dock**, so it opens like an app.

## Keep a backup
Settings → **Save backup file** now and then (for example to iCloud Drive or Documents). If you ever need it, Settings → **Open backup file…** brings everything back.

## Privacy
- Your data is stored only in Safari on your MacBook (`localStorage`), never on GitHub. Clearing Safari's website data erases it, so keep a backup file.
