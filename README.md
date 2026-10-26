# GVAS-Studio
A basic save editor for Unreal Engine games. UE5 games using newer save formats are not currently supported.

## Features

- Opens plain Unreal Engine (GVAS) saves, so alot of UE4 games just work
- Dead Island 2 saves, the checksum is fixed for you when you save
- Tree view of the whole save, double click a value to edit it
- **Export to JSON and import it back** for bulk edits. It only imports into the same kind of save, so no mixing up games
- Sizes and counts are rebuilt on save, so adding lots of items or upgrades in the JSON won't break the file
- Search, copy value / path, zoom, dark and light theme
- Lots of keyboard shortcuts, press **F1** in the app to see them all (Ctrl+O open, Ctrl+S save, Ctrl+E / Ctrl+I export / import JSON, Ctrl+F find)

## Not supported yet

- Encrypted or compressed saves that need unpacking first (Sifu for example)
- Unreal Engine 5.4 and newer
- Lies of P opens and edits fine, but its checksum isnt updated, so the game might reject an edited save

## Credits

Thanks to [hzhreal](https://github.com/hzhreal/) for the reference on the Dead Island 2 checksum and compression.

## Support

If you like it you can [buy me a coffee](https://www.paypal.com/paypalme/zCaazual).

## Disclaimer

Not responsible for any damage to your saves. Always keep a backup and edit at your own risk.
