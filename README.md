# GrooveSteps

**Free interactive drum trainer and AI-assisted music tools.** Learn drums in your browser — no app, no signup — with real-time scoring, 20+ structured lessons, the full rudiment library, and Web MIDI support so a real electronic drum kit plays the sounds and lights the pads.

🥁 **Live app:** https://groovesteps.com/drums/
🎚️ **AI music studio:** https://groovesteps.com/studio/
🌐 **Home:** https://groovesteps.com

## What's here

- **Embeddable drum-machine widget** — drop an interactive, playable beat into any page with one `<iframe>`.
- **Open practice patterns** — the lesson/groove pattern grids used by the trainer.

## Embed the widget

Add a live, playable GrooveSteps beat to your site:

```html
<iframe
  src="https://groovesteps.com/drums/embed/?p=kick,,snare,,kick,kick,snare,&bpm=90"
  width="100%" height="320" style="border:0;border-radius:12px"
  title="GrooveSteps drum machine" loading="lazy"></iframe>
```

- `p=` — comma-separated steps (voice name or empty for a rest). Up to 24 tracks.
- `bpm=` — tempo, clamped 20–400.

The widget is chrome-free and self-contained. Attribution links back to [GrooveSteps](https://groovesteps.com/drums/).

## Features

- 🎯 Original real-time scoring engine (perfect/good/ok windows, combo, S–F grades, tap-test latency calibration)
- 🎹 Play along by keyboard, mouse, or **external USB-MIDI e-kit** (General MIDI drum map)
- 📚 [20+ free interactive lessons](https://groovesteps.com/drums/lessons/) and the [rudiment library](https://groovesteps.com/drums/rudiments/)
- 🔌 Installable PWA, works offline

## License

The embeddable widget and practice patterns are released for free use with attribution to https://groovesteps.com. Built by the GrooveSteps team.
