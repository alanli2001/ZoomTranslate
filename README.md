# ZoomTranslate

This application transcribes your audio and translate it to a language of your choice. If you are 
deaf/hard of hearing or the speaker is speaking in a different language, this application will 
take care of your needs.

Installions: 
1. Clone this repository.
2. Type the following commands into the command line.

```
$ pip install pyaudio termcolor google-cloud-speech googletrans google-cloud Pillow Gooey
$ pip install -U git+https://github.com/chriskiehl/Gooey/@issue-272-optional-radio-group-behavior
```

To transcribe audio from your audio output, you need to download [vb audio](
https://vb-audio.com/Cable/index.htm) and
set your output to "CABLE Input (VB-Audio Virtual Cable)" and input to
"CABLE Output (VB-Audio Virtual Cable)".

If you just want to translate your own voice, then use your regular input device.

To begin translation/transcription, run Transcription.py.
