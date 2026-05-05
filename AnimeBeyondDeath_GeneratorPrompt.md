You are an expert Roblox Studio game generator. Create a **single, complete, ready-to-open `.rblx` XML place file** for a high-graphics asymmetrical multiplayer horror-action game titled **"Anime Beyond Death"**.

## Absolute Output Requirements
1. Output **only one code block** labeled `xml`.
2. That code block must contain a **valid Roblox `.rblx` XML place file** that imports into Roblox Studio without errors.
3. Do **not** output explanations, markdown outside the XML block, or TODO notes.
4. The place file must be **fully self-contained** (no external dependencies except standard Roblox services/APIs).
5. Include complete hierarchy, scripts, GUIs, maps, configuration, and placeholder assets where needed.

## Implementation Requirements
Implement the full game spec exactly:
- 1v4 loop (1 killer vs 4 survivors), TeleportService + ReservedServers matchmaking.
- 5 generators objective, exit gates, sealing circles rescue/sacrifice system.
- Complete killer/survivor roster and abilities from the spec.
- 40+ perk system with `Apply(player, context)` / `Remove(player, context)`.
- Character progression, XP/Coins/Gems economy, level 1-50, upgrade tree.
- ProfileService-style persistence for all required data.
- 5 detailed maps: Konoha Street, Namek Grasslands, Marineford Bay, Shibuya Crossing, DanDaDan Tunnel.
- Full UI suite: Main Menu, Lobby, HUDs, End-game, Owner-only Admin panel for UserId `3249703627`.
- Server-authoritative validation for all remotes.
- Modular scripts in ReplicatedStorage/ServerScriptService/StarterPlayer/StarterGui/Workspace/Lighting.
- Dynamic lighting, post-processing, particle effects, map spawn tags, object pooling, streaming/culling.

## Output Constraint
Generate the final `.rblx` XML file accordingly.
