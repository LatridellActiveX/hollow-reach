# Hollow Reach

A mobile-first browser space trading and mining game inspired by EVE Online and EVE Frontier. No blockchain: all state lives in your browser's local storage.

## Play

Open `index.html` in a browser, or serve the folder with any static host (see Deploy).

## Controls

- **Tap empty space**: fly there.
- **Tap an asteroid**: approach and mine it until it's depleted or your cargo is full.
- **Tap a pirate**: approach and attack it automatically.
- **Tap the station**: dock and open the station panel (market, hangar, repair, refuel).
- **Tap a gate ring**: warp to the connected system.
- **Map**: tap a system to plot an autopilot route; the ship warps through gates on its own.
- **Stop**: cancel the current target or route.

## Economy and risk

- Mine Veldite (common) and Krysite (rare, found in low-security space).
- Sell ore at stations. Low-security systems pay more.
- Spend credits on ship upgrades: cannon, mining laser, shields, armor, cargo, engine, fuel tank.
- Warps cost fuel. Refuel and repair at stations.
- High-security systems are safe. Low-security systems have pirates that pay bounties and destroy ships.
- If your ship is destroyed you lose 10% of your credits and your cargo.

## Deploy to Cloudflare Pages

    npx wrangler pages deploy . --project-name hollow-reach

## Notes

Progress saves automatically to local storage. Use "Reset universe" in the Log panel to start over.
