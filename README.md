# 🎭 Mafia Game Moderator

A simple, intuitive web app for moderating Mafia games (also known as Werewolf). Just open `index.html` in your browser and start playing!

---

## ✨ What It Does

**Add & Manage Players**
- Type names and press Enter or click + to add
- Click × next to any player to remove them
- Each player gets a random avatar emoji

**Assign Roles**
- Click **Configure Roles** to set how many of each role type
- Click **Randomize Roles** to automatically assign roles
- Toggle role visibility with the eye button

**Run The Game**
- **Night Phase**: Mafia picks victim, Doctor saves someone, Cop investigates
- **Day Phase**: Discussion and voting time
- **Game Timer**: Keep track of phase duration
- **Actions**: Kill, Save, Investigate, or Revive selected players
- **Notes**: Jot down moderator notes (auto-saved)

**Win Detection**
- Game automatically detects when Mafia or Town wins

---

## 🎮 Roles Available

| Role | What They Do |
|-------|-------------|
| 🔴 Mafia | Kills one player each night |
| 🔵 Town | Regular villager, votes during day |
| 💉 Doctor | Can save one person from Mafia each night |
| 🔍 Cop | Can investigate one player each night to see if they're Mafia |
| 🃏 Jester | Wins if voted out during the day |
| 👑 Godfather | Enhanced Mafia member, shows as Town when investigated |

---

## 🕹️ Game Phases

1. **Setup** - Add players, configure roles
2. **Night** - Special roles take action secretly
3. **Day** - All players discuss, then vote
4. **Game Over** - Winner announced!

---

## 💾 Data Features

- **Auto-save** - Everything saves to browser storage automatically
- **Export** - Download game state as JSON file
- **Persistent** - Refreshing page won't lose your game

---

## 🚀 How to Use

1. Open `index.html` in any modern web browser
2. No installation needed - it just works!
3. All data stays in your browser - nothing is sent to any server

---

## 📝 Notes

- Works offline - no internet needed after first load
- Game saves automatically after every action
- Max 100 log entries kept (older ones auto-delete)
