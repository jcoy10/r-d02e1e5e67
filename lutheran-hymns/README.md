# Lutheran Hymns

Library page for Lutheran hymn accompaniments. Open `index.html`.

## Add a hymn

1. Drop `hymn-<N>.html` into this `lutheran-hymns/` folder.
2. Add one line to the `HYMNS` array at the top of `index.html`.

```js
{ number: 621, title: "Let All Mortal Flesh Keep Silence", file: "hymn-621.html", section: "" },

```

Copy `title` from the player's heading (`Hymn 621` and the title beneath it). Use `line` when you have a first line that is separate from the title. Leave `section` as `""` to keep a single list, or set a section name to group hymns under that heading. Leave any field you do not have blank.

The page sorts by hymn number. The search box matches number and title.
