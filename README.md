# Dial Practice

A practice keypad that helps students learn the motor plan for dialing a phone number, such as 911. Each key makes its own sound and says its name, and a guide shows the way to each key, then fades as the student gets more confident.

**This is practice only. It never places a call.** A banner on every screen says so.

The design borrows the idea behind motor-planning AAC systems such as LAMP: every key stays in the same place, so the same movement always leads to the same key, and sound and sight go along with each press. This project is not affiliated with LAMP or its makers.

## Quick start

1. Open the app in a browser on a tablet, laptop, or phone.
2. Hand the device to the student. It starts at Level 1 with 9-1-1.
3. The student follows the hand and the glowing key: **9, 1, 1, then the green Call button**.
4. A practice call rings, a practice operator answers, and the screen says **Great dialing!**

To change the number, level, or sound, hold the **Settings** button for about one second (see below).

## What the student sees and hears

- **Number display.** The number to dial appears in light gray. Each digit turns dark as the student presses it.
- **Key tones.** Each key plays its own phone-keypad tone, so the sound goes with the movement.
- **Spoken digits.** The app says each digit as it is pressed, such as "nine".
- **Coach box.** A short line tells the student what to do next. The speaker button reads it aloud.
- **Wrong key.** A soft low blip plays and the key wobbles. The wrong digit is never typed, and the pleasant key tone is not played, so the student does not practice the wrong movement. The coach says "Try again."
- **Call button.** Pressing Call is the last step, so the whole sequence is practiced. The practice call rings. For 911, 112, and 999 a practice operator says "What is your emergency?" and a short reminder says to stay on the line and say where you are.

## Support levels

Start where the student can succeed, then give less help over time.

| Level | Name | What the student gets |
|---|---|---|
| 1 | Watch and follow | A hand glides to each key and taps it. A dotted arrow shows the path from the last key. Only the next key is bright. The other keys fade back. |
| 2 | Follow the glow | The next key glows and the arrow stays. No hand unless the student presses Hint. All keys work. |
| 3 | Fading help | No cue at first. The glow appears after a pause (3, 5, 8, or 12 seconds, your choice) or after two wrong presses. |
| 4 | On my own | No cues. The glow appears after three wrong presses, or when the student presses **Hint**. |
| Free dial | Free dial | Type any number and press Call. Every key still makes its own sound. |

Buttons under the coach box:

- **Watch me.** The app dials the number by itself, with the hand, tones, and a practice call, then says "Now it is your turn." Use it as a model before the student tries. Not shown in Free dial.
- **Hint.** Shows the hand, glow, and path for about 4 seconds. Not shown at Level 1 or in Free dial.
- **Start over.** Clears the number and starts again.

## Settings for grown-ups

Press and hold the **Settings** button for about one second. The hold keeps students from opening it by accident. If you use a keyboard, tab to it and press Enter.

- **Practice number.** Choose 911, 112 (Europe), or 999 (UK), or add your own, such as a family number. Use 3 to 15 digits. Check that the emergency number matches where your students live.
- **Support level.** Pick Level 1 to 4 or Free dial.
- **Sound.** Tone and voice, tone only, voice only, or silent. Set the volume, and choose whether the app says the next key out loud. The Test sound button plays a sample.
- **How keys respond.**
  - *On touch:* the key works as soon as it is touched.
  - *On release:* the key works when the finger lifts off it.
  - *Touch and hold:* the key fills up and works after a hold of 0.3, 0.5, 0.8, or 1.2 seconds.
  - *Ignore repeat touches:* off, or ignore taps that come within 0.3, 0.6, or 1 second of the last one. This can help with tremor or accidental double taps.
- **Display.** Show or hide the number to dial. Hiding it asks the student to dial from memory. Choose standard or high-contrast colors. The app also follows the device's light or dark setting.
- **Recent practice.** A table of the last 10 practice calls: when, number, level, time, wrong presses, and hints used. Watch me runs and Free dial are not logged. Clear progress takes two taps.

## Suggestions for teaching

These are suggestions, not research findings. Adjust them for each student.

- **Keep the setup the same.** The keys are always in the same order, but their size changes with the screen. Use the same device in the same orientation so the student's movements stay consistent.
- **Start with a model.** Press **Watch me** once or twice, then let the student try.
- **Move up gradually.** A simple rule is to go up a level after a few practice calls in a row with no wrong presses and no hints. Go back down a level if the student is frustrated or the wrong-press count climbs. The Recent practice table shows both.
- **Practice the whole task.** Include the Call button every time, since it is part of the movement.
- **Try the real thing.** This app uses the standard 3-by-4 layout with 1-2-3 on the top row. Real phones differ in where the call button is and how it looks. If you also practice on the student's own phone, stop before pressing the final call button. Do not rehearse by calling real emergency numbers, since accidental calls tie up emergency lines.
- **Teach the rest of the skill separately.** The app practices the dialing movement only. Knowing when to call, what to say, and where to say you are needs separate teaching.

## Keyboard shortcuts

Number keys, `*`, and `#` press the matching keys. Enter presses Call. Backspace deletes a digit in Free dial. Escape closes settings or ends a practice call.

## Privacy

Settings and practice history are saved only in the browser on that device. Nothing is sent anywhere, and the app has no accounts. Because the history is per browser, set up each device separately. Private or incognito windows may not remember settings.

## Troubleshooting

- **No sound.** Tap a key first, since browsers block sound until the first touch. Then check the device volume and that the silent switch is off. Check that Sound is not set to Silent in settings.
- **The voice sounds different on another device.** The spoken digits use the voice built into each device.
- **The number is hard to see.** Turn on high-contrast colors in settings.
- **Settings are not remembered.** The browser may be blocking site storage or running in a private window.
- **The Call button is below the screen on a phone.** Scroll down a little. On tablets and laptops the whole keypad fits.

## Running it yourself

The app is one file, `index.html`, with no install and no build step. Open the file in a browser, or host it anywhere that serves static files. With GitHub Pages, put `index.html` at the top of a repo, then go to Settings, then Pages, and deploy from the `main` branch. An internet connection is only needed to load the font. Without it the app uses the device's default font.
