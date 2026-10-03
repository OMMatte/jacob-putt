# Jacob's Putt

A silly three-green putting game for Jacob. Sink all three greens to reveal the prize.

Everything lives in `index.html` (plain HTML, CSS and JavaScript, no build step).
Open it in a browser to play, or serve the folder with any static server.

## Where things are

- **Greens:** `LEVELS` in the first `<script>` block. Each green has a shape
  (`greens`: ellipses), slopes (`terms`: `tilt`, `bump`, `tier`), bunkers
  (`sand`), water, a tee and a hole. 1 px = 5 cm; the world is 360 px wide.
- **Physics:** `roll()` (slope plus friction per surface, see `SURF`).
- **Caddie jokes:** `LINES` in the second `<script>` block.
- **Characters and twists:** the shy hole (`shy`), Gerald the duck (`duck`),
  the weak ACL knee (`acl`), the Bouncer (`keeper`) and the snapping putter (`snap`).

## Hosting

Served by GitHub Pages from the root of the `main` branch: https://ommatte.com/jacob-putt/
