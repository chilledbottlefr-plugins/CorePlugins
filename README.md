# CorePlugins Hub

Lightweight, GUI-driven Minecraft plugins built for **Paper 1.21+** servers—with zero external dependencies required.

🌐 **Download Website:** `https://github.io`

---

## Included Plugins

### 1. CorePvPplugin (`v1.0.0`)
An all-in-one PvP practice core featuring interactive chest GUIs, custom kits, and instant FFA re-gearing.
* **1v1 Duels & Global Queue (`/duel`, `/queue`):** Challenge friends or matchmake globally across *Nodebuff, UHC, Boxing,* and *Sumo*.
* **FFA Arenas (`/ffa`):** Warp into custom arenas with automatic healing, floor-drop clearing, and 100% durability kit restoration on every kill.
* **Kit Editor (`/kiteditor`):** Players customize and save their personal hotbar layouts per gamemode.
* **Parties & Spectating (`/party`, `/spectate`):** Manage parties and watch live 1v1 matches from a chest menu.
* **Stats, Leaderboard & Settings (`/stats`, `/leaderboard`, `/settings`):** Tracks Kills, Deaths, K/D Ratio, and ELO with personal preference toggles.
* **Admin Tools (`/kit`, `/arena`):** Create kits directly from your inventory and set duel/FFA spawn points in-game (`corepvp.admin`).

### 2. CoreSMPplugin (`v1.0.0`)
A complete DonutSMP-style survival economy and utility suite with built-in currency, bounties, and player markets.
* **Auction House (`/ah`, `/auction`):** List items for sale and browse live player auctions in a chest GUI.
* **Server Shop (`/shop`):** Admins add items in-game (`/shop add <price>`) for players to buy anytime (`coresmp.admin`).
* **Player Buy Orders (`/order`, `/orders`):** Create buy orders with escrow protection and deliver items directly from your inventory for instant cash.
* **Homes GUI & TPA (`/sethome`, `/delhome`, `/tphome`, `/tpa`, `/tpahere`, `/tpaccept`, `/tpadeny`):** Click beds in a GUI to teleport home or send teleport requests.
* **Live Bounties & Multi-Category Leaderboard (`/bounty`, `/leaderboard`, `/baltop`, `/bal`, `/pay`):** Stack bounties on players and browse *Most Kills, Most Deaths, Highest Live Bounty,* and *Baltop* tabs.
* **Social System (`/addfriend`, `/unfriend`, `/follow`, `/unfollow`, `/block`, `/unblock`):** Friend join/leave alerts, live world-change follow tracking, and request blocking.

### 3. CoreLifestealplugin (`v1.0.0`)
A modern Lifesteal survival plugin with physical heart items, player revives, and a live in-game admin panel.
* **Heart Stealing & Elimination:** Eliminating a player steals **1 permanent heart** (up to the server's max limit), while losing your final heart eliminates you until revived.
* **Unified Heart & Revive GUI (`/revive`):** View your hearts, withdraw physical Extra Heart items, or click eliminated player heads to revive them using a Revive Beacon.
* **Heart Withdrawal (`/heartwithdrawl <amount>`):** Convert your max health into physical Extra Heart items to trade or store safely.
* **Live Admin Panel (`/lsadmin`):** Interactive OP/admin GUI to give hearts or Revive Beacons, eliminate players from a skull selector, and adjust the **Max Heart Limit** and **Starter Hearts** on the fly (`corelifesteal.admin`).

---

## Installation
1. Download **`CorePvPplugin-1.0.jar`**, **`CoreSMPplugin-1.0.jar`**, or **`CoreLifestealplugin-1.0.jar`** from this repository or the [Download Website](https://github.io).
2. Drop the `.jar` file(s) into your **Paper 1.21+** server's `/plugins` folder.
3. Restart your server—all three plugins work out of the box with no extra dependencies!
