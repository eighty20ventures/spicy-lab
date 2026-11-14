# spicy-lab

Interaction experiments and small builds, served spicy.

Each folder is one self-contained experiment: a single HTML file, no build step, no dependencies. Open it, read it, steal the good parts.

## Experiments

### [Page not found: sticker takeover](sticker-takeover/)
A "page not found" that isn't. The copy reveals in sequence, then kitten stickers press onto the page until they take over the whole screen.

- Staged reveal with CSS animation delays
- Stickers placed on a jittered grid, shuffled, and timed so the full takeover always lands in about 4.5 seconds on any screen size
- Respects `prefers-reduced-motion`

**Use it:** download `sticker-takeover/index.html` and the `stickers/` folder, swap the images in the `IMGS` list, and change the copy.

> **Image notice:** the cat photos and the GIF in this experiment are used for illustrative purposes only. All rights belong to their respective owners. They are not covered by this repo's license and aren't offered for reuse. If you own one of these images and want it removed, open an issue and it will be taken down.

## License

Code is MIT licensed. Images and GIFs belong to their respective owners and aren't covered by the license.
