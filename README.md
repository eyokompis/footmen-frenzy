# Footmen Frenzy: Skirmish

A free, original browser RTS prototype inspired by the fast lane battles of classic Warcraft III custom games. This project uses its own simple canvas graphics and code; it does not include Blizzard assets.

## Play locally
Open `index.html` in a modern browser. No build step or dependencies are required.

## Controls
- **Choose lane:** tap North, Center, or South before recruiting; units only engage enemies in their lane.
- **Train footman:** button or keyboard `1` (50 gold)
- **Upgrade troops:** button or keyboard `2` (starts at 100 gold)
- **Upgrade barracks:** button (starts at 150 gold; up to 3 levels, faster automatic footman training and a higher troop cap)
- **Upgrade selected tower:** button (starts at 100 gold; strengthens the selected lane's tower, increasing its maximum health, shot damage, and firing speed)
- **Repair base:** button or keyboard `3` (75 gold)
- **Train ranger:** button or keyboard `4` (80 gold; ranged attacks)
- **Train knight:** button (110 gold; tough front-line unit)
- **Train mage:** button (125 gold; fragile long-range attacker)
- **Train siege engine:** button (160 gold; slow unit that deals extra base damage)
- **Hero Strike:** button or keyboard `5` (area damage, 8-second cooldown)
- **Rally:** button or keyboard `6` (nearby troops deal 50% more damage for 6 seconds; 18-second cooldown)
- **Heal Pulse:** button or keyboard `7` (heals nearby damaged troops; 20-second cooldown)
- **Unit counters:** knights are strong against ranged units, mages counter knights, and footmen deal bonus damage to siege engines
- **Restart:** button

## Current prototype
- Three separate battle lanes: North, Center, and South
- Enhanced Canvas battlefield with layered dusty roads, grass, shrubs, stones, detailed keep walls and crenellated towers
- More distinctive unit silhouettes, including knight armor, ranger bows, mage glow, siege wheels and hero crown
- Separate destructible defensive towers in all lanes
- Lane-specific tower upgrades: each level adds 10 maximum/current health, +2 shot damage, and faster firing; costs increase by 100 gold per level
- Select a lane before recruiting troops; enemy recruits are distributed across lanes
- Each lane has a defensive tower with its own health; units must destroy the tower before damaging the main base
- Surviving towers automatically fire at nearby enemy troops in their own lane
- Automatic blue vs. red troop combat
- Gold income and troop training
- Upgradeable barracks that increase automatic reinforcements and troop capacity
- Enemy AI can upgrade its barracks to improve reinforcement speed and army capacity
- Troop upgrades and base repairs
- Ranger unit with ranged attacks
- Knight, mage, and siege engine unit types
- Enemy AI that recruits different units and upgrades its army over time
- Adaptive enemy recruitment that responds to the player's unit composition
- Simple unit-counter bonuses to make army composition more tactical
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
1. Improve combat and pathing within each lane.
2. Add more hero abilities and a fuller economy.
3. Add map and game settings.
4. Explore online multiplayer after the single-player core is solid.

## License
Choose a license before accepting outside contributions. Keep third-party art, sound, and code properly licensed.