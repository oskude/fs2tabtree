# fs2tabtree

print a (filesystem) directory as html, with css based "tab tree" navigation...

_... was just wondering if this was possible without (client side) javascript._

```
./fs2tabtree /usr/share/icons > wut.html
firefox wut.html
```
![screenshot](screenshot.png?raw=true)

> **NOTE!** first prototype, works-for-me with one example...

## blah
- watsmacallit? ive seen it before...
- document the "magic", i think its pretty cool...
  - basically: `<input type=radio>`'s `checked` state, flex order and wrap...
- flaky!!! cause no `lh` css unit yet...
   - if a dir "tab" is in wrong place, try wiggle the `section` `font-size`...
