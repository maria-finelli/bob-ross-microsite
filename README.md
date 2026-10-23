# The Joy of Painting — A Bob Ross Experience

An unofficial fan tribute to _The Joy of Painting_, staged like the show's black studio set.

## What's on the page

- **Episodes**: 387 of the 403 episodes across all 31 seasons. Each card plays the official upload from the [Bob Ross YouTube channel](https://www.youtube.com/@bobross_thejoyofpainting) in a modal.
- **Bob Ross Radio**: the real show back to back through the YouTube IFrame API, with stations (all seasons, early, middle, final, winter scenes), previous/next and an up-next queue.
- **Studio soundboard**: eight brush, knife and easel sounds synthesized in the browser, plus four real squirrel recordings in `sounds/` (Peapod chatter, treetop chirps, snack time, alarm call).
- **Paint a happy little scene**: a canvas generator for happy trees, bushes, mountains and clouds over four skies. Save as PNG.

## Running locally

The YouTube player won't start from a `file://` page, so serve the folder:

```sh
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Data

Episode ids come from the official channel's season playlists (`EPISODES` in `index.html`: season, episode, title, video id). Every id was checked as embeddable on 2026-10-23. Thumbnails load from `i.ytimg.com`.

## Credits

Squirrel recordings from Wikimedia Commons:

- `peapod-grey-squirrel.mp3`: [Grey Squirrel (Sciurus carolinensis)](<https://commons.wikimedia.org/wiki/File:Grey_Squirrel_(Sciurus_carolinensis)_(W1CDR0001470_BD12).ogg>), British Library, CC BY-SA 4.0
- `treetop-chirps.mp3`: [Three Squirrels chirping](https://commons.wikimedia.org/wiki/File:Three_Squirrels_chirping.ogg), Jidanni, CC BY-SA 4.0
- `snack-time.mp3`: [A squirrel chirping while eating a pomegranate](https://commons.wikimedia.org/wiki/File:A_squirrel_chirping_while_eating_a_pomegranate,_Bangalore,_India.flac), Subhashish Panigrahi, CC BY-SA 4.0
- `douglas-alarm.mp3`: [Tamiasciurus douglasii](https://commons.wikimedia.org/wiki/File:Tamiasciurus_douglasii.ogg), Parande, CC BY-SA 3.0

Bob Ross and The Joy of Painting are trademarks of Bob Ross Inc. This site is not affiliated with Bob Ross Inc.
