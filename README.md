# AuctionManagement

A control room for running a college IPL-style player auction from one laptop. It is a single HTML file: no server, no install.

**Open `index.html` in Chrome, Edge or Firefox.** It starts with a sample auction (8 made-up teams, 79 made-up players) so you can try everything. Clear it with the **SAMPLE DATA** button, or in **Setup → Backup & reset**.

## What it does

- **Control room**: the player on the block, current bid, timer, one-click team bids, SOLD / UNSOLD / UNDO / PASS / RTM, team purses, the next-players queue and a live feed, all on one screen.
- **Budget safety**: blocks bids over a team's purse or past its squad, overseas or role limits, and warns about low purses and unmet role minimums.
- **Right to Match**, with an optional final raise.
- **Mystery players**: hidden identity and clues, then a reveal. Blind bidding, with the reveal on sale, is also an option.
- **Wild cards**: surprise players brought in with a 3-2-1 countdown.
- **Projector view**: press `V`, or open the page in a second window with `#projector` at the end of the address.
- **Corrections**: change a team or price, re-auction, send to the unsold pool, adjust purses, restore an earlier state. Nothing is deleted from the history.
- **Reports and judging**: team reports, auction statistics, a judging panel out of 100, and fun awards.
- **Exports**: CSV, Excel and PDF. Excel and PDF need internet the first time.

## Keyboard shortcuts

| Key | Action |
| --- | --- |
| `Space` | Next bid (the other team in a bidding war comes back in) |
| `1`–`9`, `0` | Bid for teams 1–10 |
| `Shift+1`–`5` | Bid for teams 11–15 |
| `S` / `U` | Sold / unsold |
| `R` | Undo |
| `N` / `P` | Next / previous player |
| `M` / `Shift+M` | Mystery: next clue / reveal |
| `W` | Wild card |
| `T` | Right to Match |
| `C` | Custom bid |
| `X` | Pass |
| `A` | Breaking news alert |
| `V` / `F` | Projector view / full screen |
| `Enter` / `Esc` | Confirm / cancel |

## Saving

Every action saves instantly in the browser the auction runs in, and the auction comes back after a refresh or a crash. That storage belongs to one browser on one laptop, so use **Export backup** (in Setup → Backup & reset, or Reports) before the event and at breaks. **Restore backup** loads it on any machine.

## Importing players

Use a CSV or Excel file with a header row. Recognised columns: Player ID, Name, Role, Batting, Bowling, Rating, Base Price, Category, Overseas, Tags, Mystery, Wild Card, Set, RTM Team, Clues, Photo URL. Separate several tags or clues with `|`. **Players → CSV template** downloads an example file.
