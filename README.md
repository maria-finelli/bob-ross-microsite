# A Little Bob Ross Project 🎨

A playful, single-page tribute to someone who made creating things feel a little less intimidating.

## Why I made this

I watched Bob Ross growing up, and I’m still amazed by him as an adult. He’d start with a blank canvas and casually pull an entire world out of it, all while telling you that you could do it too. Like it was no big deal.

That always stuck with me. The kindness, the humility and the way he made room for anyone to try.

I wanted to make a little place on the internet that captures some of that feeling. Somewhere you can hang out, play with familiar sounds, discover a painting and enjoy a quiet moment.

## What’s inside

Part dashboard, part little corner of his studio, set against the show’s black backdrop so the paintings carry all the color.

- **Today’s episode:** A different painting sits on the easel each day, ready to watch whenever you want to settle in.
- **The painting library:** 387 episodes across all 31 seasons of _The Joy of Painting_, browsable by season. Every one plays right on the page, streamed from the official [Bob Ross YouTube channel](https://www.youtube.com/@bobross_thejoyofpainting).
- **Bob Ross Radio:** The loungey, jazzy music from the show. It opens on the theme, “Interlude” by Larry Owens, then plays the rest of his 1982 album _Light Lounge_. Or switch to a station of full episodes (the early years, the final seasons, winter scenes and more) and leave Bob on while you work.
- **An ASMR soundboard:** Sky strokes, fan brush taps, knife mixing, a mountain pull, a swish in the thinner and a good “beat the devil out of it.” Plus a squirrel corner with real recordings, including one for Peapod. Layer as many as you like.
- **Paint a happy little scene:** Click to plant happy trees, little bushes, mountains and clouds under four different skies. Drag to grow a whole forest, hit “Happy accident” for a surprise and save what you make.
- **A word from Bob:** A few of his quotes, drifting by at the bottom of the page.

## Running it locally

The episode player needs a web address rather than a local file, so serve the folder:

```sh
python3 -m http.server 8080
```

Then open http://localhost:8080.

## Credits

Episodes and thumbnails stream from the official Bob Ross YouTube channel. Studio music streams from the official [Larry Owens](https://www.youtube.com/channel/UCjZpA-PrdQkWMRVISR1BhSA) channel on YouTube (Light Lounge, ℗ 1982 UPM-US). “Interlude” is the show’s theme; the rest of the album may not all have aired. Brush and knife sounds are generated in the browser.

Squirrel recordings from Wikimedia Commons:

- **Peapod:** [Grey Squirrel (Sciurus carolinensis)](<https://commons.wikimedia.org/wiki/File:Grey_Squirrel_(Sciurus_carolinensis)_(W1CDR0001470_BD12).ogg>), British Library, CC BY-SA 4.0
- **Treetop chirps:** [Three Squirrels chirping](https://commons.wikimedia.org/wiki/File:Three_Squirrels_chirping.ogg), Jidanni, CC BY-SA 4.0
- **Snack time:** [A squirrel chirping while eating a pomegranate](https://commons.wikimedia.org/wiki/File:A_squirrel_chirping_while_eating_a_pomegranate,_Bangalore,_India.flac), Subhashish Panigrahi, CC BY-SA 4.0
- **Alarm call:** [Tamiasciurus douglasii](https://commons.wikimedia.org/wiki/File:Tamiasciurus_douglasii.ogg), Parande, CC BY-SA 3.0

---

An independent fan project, made with appreciation. Not affiliated with or endorsed by Bob Ross Inc.
