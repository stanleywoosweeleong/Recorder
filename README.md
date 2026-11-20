# Soprano Recorder 竖笛

A playable soprano recorder in one web page. Tap the holes to cover them, hold **Blow** to play, use the fingering chart, or practise songs (小星星, 玛丽有只小羊羔, 欢乐颂, 茉莉花) with on-screen fingering guides.

**Play it:** https://stanleywoosweeleong.github.io/Recorder/

It is an installable app (PWA) that works offline. Open the link once while online; after that it runs with no internet, even in airplane mode. The bottom of the page says "Saved on this device: works offline" when it is ready.

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

## Metronome 节拍器
Press **Start** in the Metronome panel (or **M** on a keyboard, or **♩** in Finger mode). Set the speed with − / +, the slider, or **Tap tempo**; pick 2/4, 3/4 or 4/4 for the accented first beat; **Use song tempo** matches the selected song. While a song plays (Listen) you can turn the metronome on or off at any time; it switches to the song's tempo and comes in on the song's next beat.

## On a computer
Keys A S D F G H J K L ; ' play the natural notes, W E T Y U O P the sharps, 1–7 play 简谱 notes (Shift for the upper octave), and Space blows the fingering shown.

## Updating the app
No build step and no version number to bump. Edit and push; GitHub Pages publishes in a minute or two. Phones open the saved copy instantly, check for a new one in the background, and show "A new version is ready" with a Refresh button.

Files: `index.html` (the whole app), `sw.js` (offline cache), `manifest.webmanifest` and `icons/` (install as an app), `fonts/` (local copies so text looks right offline).
