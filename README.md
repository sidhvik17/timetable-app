# Daily Timetable

A personal schedule tracker built as a single-page web app. Deployed on Vercel and installable as a PWA on iPhone.

**Live:** https://timetable-app-three.vercel.app

## Features

- **Auto-shifting schedule** — check any block done early or late and all following blocks cascade automatically
- **College locked at 9–3:30** — fixed start time, won't shift regardless of morning cascade
- **Gym locked at 1.5h** — duration never changes, only start time shifts
- **Contest slots** — LeetCode Weekly (Sun 8 AM IST) and Codeforces / LC Biweekly (Sat 8 PM IST) built in
- **Flexible sleep** — 6h on weekdays, up to 8h on weekends
- **Day progress tracker** — checkable blocks with progress bar
- **Reset Shifts** — one tap to revert all time adjustments for the day
- **PWA / iPhone shortcut** — add to home screen via Safari for a full-screen app experience

## Schedule

| Day | Highlights |
|-----|------------|
| Mon–Fri | College 9–3:30 → Gym 4–5:30 → Study/ML/Backend → Sleep 12 AM |
| Saturday | Deep study + Gym 4–5:30 + Codeforces / LC Biweekly 8 PM |
| Sunday | LeetCode Weekly Contest 8 AM + Deep study. No gym. |

## iPhone Setup

1. Open the live URL in **Safari**
2. Tap **Share → Add to Home Screen**
3. Tap **Add** — opens as a full-screen app

## Deploy your own

```bash
npm i -g vercel
vercel --yes
```
