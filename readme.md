# fs2tabtree

print a (filesystem) tree as html, with css based "tab tree" navigation...

_... was just wondering if this was possible without (client side) javascript._

> TODO: not really feasible without `lh` css unit? so until `lh` is [implemented](https://bugzilla.mozilla.org/show_bug.cgi?id=1310170), i added a `lh2px` javascript function...

```
./fs2tabtree /usr/share/icons > wut.html
firefox wut.html
```
![screenshot](screenshot.png?raw=true)

## blah
- watsmacallit? ive seen it before...
- document the "magic", i think its pretty cool...
  - basically: `<input type=radio>`'s `checked` state, flex order and wrap...
- TODO: re-run hl2px on changes... or just wait for `lh` to get implemented ;P
- hmm, "zooming" smaller breaks it, but bigger does not!?
