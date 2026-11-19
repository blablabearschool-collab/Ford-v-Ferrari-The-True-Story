# blablabear school · Ford v Ferrari · The True Story

A new self-contained interactive English lesson for GitHub Pages, adapted to the user-provided six-episode video transcript and tasks. This is a **new** lesson; it does not overwrite the previous Ford v Ferrari website.

## Publish to GitHub Pages

1. Unzip the download in Finder.
2. Open the extracted folder and upload its **contents** (the `index.html` file and the complete `assets/` folder) to the root of a new GitHub repository. Do **not** upload the ZIP by itself.
3. In GitHub, open Settings → Pages, publish from `main` and `/ (root)` if necessary.
4. After deployment, test the embedded YouTube chapter players on the public HTTPS URL.

## How the lesson works

- The original school mascot remains unchanged in the fixed header. The hero image is the newly supplied bear at the racetrack.
- Warm-up (three questions): tap a car to reveal a prompt. Vocabulary stays visible. Clicking English expressions speaks them in American English using the browser's available voices (rather than a copied Cambridge recording).
- Five video sections based on the single YouTube documentary (`OowTNfWes4g`): 00:00–01:56; 01:57–03:05; 03:06–03:45; 03:46–06:12; 06:12–07:05. The supplied transcript has been converted into 54 time-coded English caption cues; an additional WebVTT file is included in `assets/`. The independent caption panel can be toggled on and off below each video and follows the YouTube player time when the IFrame API is available.
- True/False, 11 three-column phrase matching rows, 7 Shelby vocabulary questions, 10 vocabulary questions, 5 meaning questions, and 6 + 8 text gaps: **63 marked responses**, with immediate correct/incorrect feedback.
- Matching columns can be dragged or swapped with clicks/taps; ▲ ▼ controls are an additional option. A moved item stays where the student puts it until changed.
- Story gaps can be filled by drag-and-drop, tapping a word then a gap, or choosing from a dropdown. No question numbers are rendered inside the passage.
- Unlimited replay with no JavaScript confirmation dialogs. Each exercise has a reset button; the whole lesson can be reset at the end. Progress and optional speaking notes are stored in local browser storage.
- The final panel allows entry of a student name and one-click offline PDF download that contains the score and student responses. The PDF is **not sent automatically**: it should be attached to a message to the teacher.

## Important video limitations

The YouTube video is hosted by YouTube, not by GitHub Pages. Browser privacy settings, the owner's restrictions and certain local `file://` previews can prevent embedded playback (e.g. YouTube error 153). Each video section includes a direct `Watch on YouTube` link with the correct start timestamp as fallback. Captions under the player are synchronised with the provided transcript when the YouTube IFrame API works. If the video embed is blocked, captions can be explored using the chapter scrubber, but live playback synchronisation is unavailable.

Do not rename the `assets/` directory or move it away from `index.html`.
