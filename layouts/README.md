# uPedal community layouts

The catalogue uPedal's Share Layout > Community tab reads: `index.json` lists
every shared plug-in layout with its title, author, tags, notes and the
SHA-256 of its file; the files sit beside it, one directory per plug-in.

uPedal downloads `index.json` only when a player taps "Look for layouts",
keeps the entries for the plug-in in front of them, checks each file's
checksum before using it, and opens it as a draft to review. Nothing about a
player's rig is sent.

The catalogue is empty for now. It is built from exported layout files with
`scripts/layouts/build-community-index.py` in the uPedal repository; the
format and the process are in its `docs/design/layout-studio/community-index.md`.
