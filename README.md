# Erogodox Mappings

Keymappings for ergodox/iris keyboards. These are backups/quick access points. The Wally tool provided by ergodox-ez can be used to flash either keyboard.

## Configuring

### Rev8

https://www.caniusevia.com/ to edit the board directly. If you get errors when plugging in, you will need to:
- check `chrome://debug-log` to look for the `/dev` device that couldn't be opened
- `chown $USER:$USER /dev/...`
- open the browser from that active terminal tab

Remember to use a chromium based browser like Vivaldi

### Rev4 & Dox
Visit the [QMK Config Tool](https://config.qmk.fm/#/keebio/iris/rev4/LAYOUT) and upload the link to the raw `keymap.json` file for the board being modified. Make sure the right board is picked (`keebio/iris/rev4` or `ergodox_ez`)

Once ready, download both the map & firmware for persisting here

### Flashing

Plugin board, boot Wally, pick hex, hit reset.
