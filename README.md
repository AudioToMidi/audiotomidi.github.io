Audio to MIDI — Convert Audio into Editable MIDI Notes

Website: https://audiotomidi.github.io

Audio to MIDI is a browser-based music tool designed to help musicians, producers, and composers convert audio recordings into MIDI notes directly in their browser.

Powered by Spotify’s open-source Basic Pitch model and TensorFlow.js, the project detects musical notes from audio and allows users to adjust the detected notes to fit a selected musical key and scale.

Key Features

* Audio-to-MIDI conversion: Detect musical notes from supported audio recordings.
* In-browser processing: Audio processing runs in the browser, without uploading recordings to a remote server.
* Key and scale correction: Snap detected notes to a selected scale to help keep MIDI melodies in key.
* Piano roll visualization: View detected notes and identify notes that have been moved into the selected scale.
* MIDI export: Download the converted notes as a MIDI file for use in a digital audio workstation (DAW).
* Audio playback: Listen to the original recording and preview the detected MIDI notes.
* Customizable detection: Adjust onset sensitivity, sustain sensitivity, note length, and minimum velocity.
* Timing controls: Configure tempo, quantization, note range, and minimum note duration.
* Responsive interface: Use the tool on desktop and mobile devices.
* Light and dark modes: Choose a theme that suits your preference.

Who Is It For?

Audio to MIDI is designed for music producers, songwriters, musicians, composers, and anyone who wants to turn musical recordings into editable MIDI data.

It can be useful for extracting melodies, transcribing instrumental parts, experimenting with harmonies, and developing musical ideas in a DAW such as REAPER, FL Studio, Ableton Live, or Logic Pro.

Technology

* Basic Pitch by Spotify — Open-source audio-to-MIDI note transcription.
* TensorFlow.js — Machine learning capabilities in the browser.
* HTML, CSS, and JavaScript — Web interface and application functionality.
* GitHub Pages — Website hosting.

Important Notes

Conversion accuracy depends on the audio source. Clear, isolated instruments generally produce better results than dense mixes containing multiple instruments, vocals, and drums. The generated MIDI may require additional editing before use in a music production project.

Open-Source Credits

This project uses Spotify’s Basic Pitch under the Apache License 2.0 and TensorFlow.js. Please refer to the respective projects for their license terms and attribution requirements.

Try It Online

Visit https://audiotomidi.github.io to explore the tool and convert your audio recordings into MIDI.

Created with love by Lai Honest.
