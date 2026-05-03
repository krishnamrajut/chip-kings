What It Does
After every card game session, figuring out who owes whom can get messy — especially with a pot, food expenses, and multiple players. Chip Kings handles all of it automatically:

Enter each player's starting and final chip counts
The app calculates who pays whom with the minimum number of transactions
The Pot automatically covers any chip shortfall, or collects any surplus
Food & other expenses are tracked separately and reimbursed from the Pot
Share the settlement instantly via WhatsApp
Every session is saved with full history and trends


Features
♠ Settle Tab
FeatureDetailsPlayer cardsSelect from the group roster or type manually. Duplicate names are prevented across dropdowns.Starting chipsDefaults to 250. Adjustable per session.Final chip countEnter each player's count after the game. Live win/loss indicator updates as you type.PotEnter the remaining chips in the pot. Final pot count calculated automatically.Food & Other ExpensesAdd one or more payers with their amount. Pot reimburses each payer in the settlement.Venue & DateTag each session with a venue (e.g. "KR's House") and date.SettlementCalculates minimum transactions to settle all balances. Pot pays winners if losers can't cover, or collects surplus if losers paid more than winners took.WhatsApp ShareOne tap sends a formatted settlement message to the group chat.
📅 History Tab

Full session history sorted by date
Each session shows players sorted highest winner → biggest loser
Food expenses shown with who paid
Settlement tracker — mark each payment as Paid ✅ or Pending
Edit any session to correct player nets, food amount, or venue
Export backup (JSON) and Import backup to sync between devices
Export CSV for spreadsheet use

📊 Trends Tab

Overview — sessions played, players tracked, top earner and "needs a comeback" player with funny rotating Telugu + English tags
All-time chip tally — ranked leaderboard with funny player tags, W/L record, progress bars
Current streaks — who's on a winning or losing streak
Running total line chart — cumulative chips per player across all sessions
Session dots — one dot per game night, green = won, red = lost


Player Roster
Manual Entry, PP, KR, K1, K2, PV, MM, CP, SG, VK, RM, RA.

How to Use
Starting a new session

Select number of players from the dropdown
Adjust Starting chips if different from 250
Pick each player's name from their card dropdown
After the game, enter each player's Final chips
Enter Pot final chips if known (leave 0 if unknown)
Add any Food & Other Expenses with who paid
Enter the Venue and confirm the date
Hit ♠ Settle Up
Review the settlement, then tap 💾 Save and Share on WhatsApp

Syncing between laptop and phone
Since data is stored in your browser's local storage, use the Export/Import feature to sync:
Laptop → Phone:

History tab → ⬇ Export backup → saves a .json file
WhatsApp the file to yourself
Open on iPhone → History tab → ⬆ Import backup
New sessions are merged in — no duplicates, no data loss

Updating the app
When a new version of index.html is available:

Go to github.com/krishnamrajut/chip-kings
Click index.html → click the ✏️ pencil icon
Select all → paste the new content → Commit changes
Wait ~1 minute → live at the URL automatically


Pot Logic
The Pot acts as a balancer to ensure all settlements are fair:
ScenarioWhat happensTotal lost > Total wonSurplus chips go to the PotTotal won > Total lostPot pays the difference to winnersPot balance set to 0Pot draws from an imaginary reserve to cover winnersFood expenses enteredPot reimburses each payer as a separate settlement transaction

Tech Stack

Pure HTML + CSS + JavaScript — no frameworks, no dependencies
localStorage for persistent session data
Single file — works completely offline after download
Hosted on GitHub Pages — free, no server needed


Access
PlatformHow💻 Laptop / DesktopOpen https://krishnamrajut.github.io/chip-kings in any browser📱 iPhoneOpen the URL in Safari → Share → Add to Home Screen📱 AndroidOpen in Chrome → Menu → Add to Home Screen💾 OfflineDownload index.html and open directly in any browser

Group
Chip Kings — a group of friends who play cards regularly and take their settlements very seriously 🃏
Built with ♠ and a lot of chip counting.
