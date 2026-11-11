# DashWorld

A Roblox-style browser game platform.

Play, build, and hang out with friends — all in the browser.

## Features

- Accounts, friends, and display names
- 3D obbies, tycoons, and community games
- Full Studio to build and publish games
- Templates (Void, Obby, Baseplate)
- Public Models — upload builds and use other people’s models
- Avatar maker, shop, UGC items
- Lua scripting
- Multiplayer servers (when online)

## Run it

Open `index.html` in a browser, or host the folder on GitHub Pages.

No install or build step needed.

## Notes

- Online features (accounts, shared games, public models) use Supabase.
- If online publish fails, check your Supabase RLS policies and allow writes for the anon key.
- Without online access everything still works in local/solo mode (saved in the browser).
