# Nexmo NCCO Examples

Welcome! Here you will find some examples of NCCOs (Nexmo Call Control Objects) that you can use with the [Nexmo Voice API](https://developer.nexmo.com/voice/voice-api/overview). We've split the examples into sections so have a browse and if you don't find what you're looking for, [open an issue](https://github.com/nexmo-community/ncco-examples/issues) (pull requests are welcome too!).

## Talking

These examples use the `talk` action, producing text-to-speech output.

- [`talk.json`](talk.json) for simple spoken words
- [`text-to-speech.json`](text-to-speech.json) also specifies a [voice name](https://developer.nexmo.com/voice/voice-api/guides/text-to-speech#voice-names)
- [`ssml.json`](ssml.json) has an example with some [SSML (Synthesized Speech Markup Language)](https://www.w3.org/TR/speech-synthesis11/) for expression.
- [`long-tts.json`](long-tts.json) specifies a voice name and a message that is repeated 10 times using the `loop` property.

## Telephone

- [`connect-phone.json`](connect-phone.json) to connect the answered call to another number
- [`connect-to-app.json`](connect-phone.json) to connect the answered call to an application using our Conversation API
- [`conference.json`](conference.json) to add every user to the same conference
- [`dtmf-input.json`](dtmf-input.json) if you want to get the user to enter some digits with their telephone keypad
- [`transfer.json`](transfer.json) to share a message when a `transfer` action has finished

## Record

- [`record.json`](record.json) will record your call. Take a look at the [code snippets](https://developer.nexmo.com/voice/voice-api/code-snippets/download-a-recording) for examples of how to authenticate and download the finished recording after the call.

## Audio

- [`silent-loop.json`](silent-loop.json) streams a mp3 file with no sound, on a loop. Useful for keeping a call active while waiting for another event to occur.

## Further Reading

Still looking for more? Try these:

- [Getting Started with Voice API](https://developer.nexmo.com/voice/voice-api/overview#getting-started) on the Nexmo Developer Platform
- [NCCO Reference](https://developer.nexmo.com/voice/voice-api/ncco-reference) for all the details on all the available parameters
