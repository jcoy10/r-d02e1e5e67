# LSB Hymns

Library page for Lutheran Service Book accompaniments. Open `index.html`.

## Add a hymn

1. Drop `LSB<N>_player.html` into this `lsb-hymns/` folder. Do not edit the player.
2. Add one line to the `HYMNS` array at the top of `index.html`.

```js
{ number: 621, title: "Let All Mortal Flesh Keep Silence", tune: "PICARDY", file: "LSB621_player.html", section: "" },
```

Copy `title` and `tune` from the player's `<title>` or `<h1>` (`LSB 621 · Let All Mortal Flesh Keep Silence (PICARDY)`). Use `line` when you have a first line that is separate from the title. Leave `section` as `""` to keep a single list, or set an LSB section name to group hymns under that heading. Leave any field you do not have blank.

The page sorts by LSB number. The search box matches number, title, tune, and first line.
