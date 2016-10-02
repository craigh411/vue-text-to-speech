# Vue Text To Speech Component

A component for Vue.js to simplify SpeechSynthesis API.

### Browser Compatability

The SpeechSynthesis API is applied inconsistently among browsers. Most issues occur for non-English text or when the native voice isn't being used. I'll list issues as I find them here. 

#### Chrome Inconsistencies and Bugs

- Chrome for Windows does not fire the onboundary event for anything other than the native voice. This means that the 'tts-word' event will not fire in chrome when using any language other than US English (en-US)


### Opera

- Opera only supports the native voice which is Us English, so is only appropriate for English text.

### Firefox

- Firefox requires that text to speech is manually activated by the user, so most FireFox users will not have text to speech features available.

### IE

### Notes about iOs

- Chrome for iOS appears to have the same support as Safari.
