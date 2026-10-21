# Footmen Frenzy: Skirmish

A free, original browser RTS prototype inspired by the fast lane battles of classic Warcraft III custom games. This project uses its own simple canvas graphics and code; it does not include Blizzard assets.

## Play locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Controls
- **Train footman:** button or keyboard `1` (50 gold)
- **Upgrade troops:** button or keyboard `2` (starts at 100 gold)
- **Repair base:** button or keyboard `3` (75 gold)
- **Train ranger:** button or keyboard `4` (80 gold; ranged attacks)
- **Train knight:** button (110 gold; tough front-line unit)
- **Train mage:** button (125 gold; fragile long-range attacker)
- **Train siege engine:** button (160 gold; slow unit that deals extra base damage)
- **Hero Strike:** button or keyboard `5` (area damage, 8-second cooldown)
- **Rally:** button or keyboard `6` (nearby troops deal 50% more damage for 6 seconds; 18-second cooldown)
- **Heal Pulse:** button or keyboard `7` (heals nearby damaged troops; 20-second cooldown)
- **Restart:** button

## Current prototype
- Automatic blue vs. red troop combat
- Gold income and troop training
- Troop upgrades and base repairs
- Ranger unit with ranged attacks
- Knight, mage, and siege engine unit types
- Enemy AI that recruits different units and upgrades its army over time
- Active Hero Strike ability with cooldown
- Rally ability to temporarily boost nearby troop damage
- Heal Pulse ability to restore nearby troop health
- Hero XP and levels gained from both normal kills and Hero Strike
- Hero respawn after being defeated
- Separate health indicators for both bases
- Victory/defeat state
- Responsive touch-friendly layout and keyboard shortcuts

## Publish for free with GitHub Pages
1. Open the repository **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose branch `main` and folder `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. The URL will be shown on the Pages settings screen.

GitHub Pages availability depends on repository/account settings. This prototype is static and does not need a server.

## Roadmap
1. Improve combat and pathing.
2. Add more hero abilities and a fuller economy.
3. Add map and game settings.
4. Explore online multiplayer after the single-player core is solid.

## License
Choose a license before accepting outside contributions. Keep third-party art, sound, and code properly licensed.