# fs2tabtree

print a (filesystem) tree as html, with css based "tab tree" navigation...

_... was just wondering if the ui was possible without (client side) javascript._

> TODO: not really feasible without [`lh`](https://developer.mozilla.org/en-US/docs/Web/CSS/length#lh) css unit? so until its [implemented](https://bugzilla.mozilla.org/show_bug.cgi?id=1310170), i added a `lh2px` javascript function...

```
./fs2tabtree /usr/share/icons > wut.html
firefox wut.html
```
![screencap](screencap.gif?raw=true)

## blah
- watsmacallit? ive seen it before...
- now with minimize toggle, to hide non selected nodes. niiiiice!
- document the "magic", i think its pretty cool...
  - basically: radio's checked state, flex order and wrap...
- TODO: re-run hl2px on changes... or just wait for lh to get implemented ;P
- hmm, client zooming smaller breaks the layout, but bigger does not!?
