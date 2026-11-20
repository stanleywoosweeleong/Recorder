# Soprano Recorder 竖笛

A playable soprano recorder in one web page. Tap the holes to cover them, hold **Blow** to play, use the fingering chart, or practise songs (小星星, 玛丽有只小羊羔, 欢乐颂, 茉莉花) with on-screen fingering guides.

**Play it:** https://stanleywoosweeleong.github.io/Recorder/

It is an installable app (PWA) that works offline. Open the link once while online; after that it runs with no internet, even in airplane mode. The bottom of the page says "Saved on this device: works offline" when it is ready.

## Share 分享
The **Share** section (also the ↗ Share button at the top) has a QR code for this repository, a **Send on WhatsApp** button with a ready-made message in the current language, **Copy link**, and on phones that support it, the phone's own share sheet. The QR code is built into the page, so it shows even offline.

## Languages 语言 · Bahasa
The app speaks **中文, English and Bahasa Melayu**. On the very first launch a full-screen picker asks which one; the choice is remembered on that device. Change it any time with the **Language** menu at the top of the page.

## On a phone
1. Open the link above in Safari (iPhone) or Chrome (Android).
2. Turn the ringer/silent switch off on iPhone, or web audio may be muted.
3. Add it to your home screen (Share → Add to Home Screen, or ⋮ → Add to Home screen) to open it like an app.
4. Tap **Finger mode · 手指模式** for a full-screen recorder you play like the real one:
   - **Touch 触摸**: place your fingers on the holes. Sound plays while any finger is down, and the pitch follows the holes you cover. Tap empty space to tongue a repeated note. The small ½ pads half-cover the thumb, 6 and 7 holes.
   - **Mic 吹气**: allow the microphone, keep your fingers on the holes, and blow gently across the bottom of the phone. Say "tu" to tongue notes. Adjust Sensitivity if it starts too easily or too late.
   - **Hold it like a recorder (portrait):** hold the phone upright, left hand on holes 1–3, right hand on 4–7, left thumb on T. Press **Flip ⇅** to move the mouthpiece to the bottom of the screen, by the phone's microphone, and blow there in Mic mode. Only the recorder flips; the text stays upright.
   - **Flat on a table (landscape):** turn the phone sideways and the recorder lies flat with the mouthpiece on the left, so the fingers of both hands rest in a row. Low C needs all 8 fingers on the screen.

## If Listen's fingers don't match the sound
Phones and Bluetooth speakers play sound a little late, and iPhone Safari doesn't report how late. Press **Tap to sync** (next to Volume, or in Finger mode), then tap the button on each of the 10 clicks. The app measures your delay and sets **Finger sync** for you. You can still fine-tune the slider: right if the fingers move too early, left if too late.

## Practise with your real recorder 真竖笛
In **Real recorder**, press **Start listening** and play your own recorder near the phone. It shows the note, a tuning needle in cents (sharp: blow more gently; flat: a little more air), how steady the note is, and whether it started cleanly. It also shows that note's fingering on the recorder. In the songbook choose **My real recorder**, then Practice or Play along listens to your instrument. Works offline; nothing is recorded or sent anywhere.

## Songbook 练习曲
12 songs, in 简谱, staff notation (五线谱) or both:
- **Listen**: hear the song while the fingers move.
- **Practice**: play note by note, at your own pace.
- **Play along**: a bar of count-in, then play in time with the metronome. You get a score for each note (perfect, good, early, late, wrong, missed) and a star rating. Best scores are saved per song.
- **Speed**: 40%–120%. **Loop**: tap the first and last note of a hard section to repeat just that part.
- **Add your own song** in 简谱 (1–7, 0 rest, ' and , for octaves, # and b, - _ . for lengths, | for bars).

## Breath, touch and vibration
- In Finger mode's **Mic** mode, breath strength matters: more air goes sharp and louder, and too much on a low note squeaks up an octave; too little goes flat and airy. The breath gauge shows the right amount for each note.
- **Leaks**: a finger off the centre of a hole leaks like a real one (sharp, hissy, orange glow).
- **Fit to hand**: touch where each finger rests and the holes move to fit your hand.
- **Vibration** (Android): a tick when a finger lands on a hole, a metronome pulse, and a buzz on wrong notes. On iPhone only the hole tick works (iOS 18+).
- **Alto recorder (F)** as well as soprano (C), Baroque or German fingering, with fingerings checked against Wikipedia's fingering table and recorderhomepage.net.

## Metronome 节拍器
Press **Start** in the Metronome panel (or **M** on a keyboard, or **♩** in Finger mode). Set the speed with − / +, the slider, or **Tap tempo**; pick 2/4, 3/4 or 4/4 for the accented first beat; **Use song tempo** matches the selected song. While a song plays (Listen) you can turn the metronome on or off at any time; it switches to the song's tempo and comes in on the song's next beat.

## On a computer
Keys A S D F G H J K L ; ' play the natural notes, W E T Y U O P the sharps, 1–7 play 简谱 notes (Shift for the upper octave), and Space blows the fingering shown.

## Updating the app
No build step and no version number to bump. Edit and push; GitHub Pages publishes in a minute or two. Phones open the saved copy instantly, check for a new one in the background, and show "A new version is ready" with a Refresh button.

Files: `index.html` (the whole app), `sw.js` (offline cache), `manifest.webmanifest` and `icons/` (install as an app), `fonts/` (local copies so text looks right offline).
