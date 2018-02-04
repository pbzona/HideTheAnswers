# HideTheAnswers

This is a Chrome extension that hides the answers on Linux Academy quizzes while taking them in admin mode.

To enable, go to `chrome://extensions/` and enable developer mode. Click **Load unpacked extension...** and select the directory where this is stored. You can also do it the right way - package it and install it properly - but it's arguably not worth the trouble.

## Things to know

This extension removes the "correct" tags after pageload, so you'll still see them flash on screen for a moment.

Currently looking for a way to prevent the label from being applied to begin with, rather than applying a new style after pageload. For now, look away from the screen while you're loading new questions.