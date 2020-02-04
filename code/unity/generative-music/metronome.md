# Metronome

Writing a reliable metronome can't be done on the main Unity udpate thread. There are some approaches, using the dsp thread:

* [AudioSource.PlayScheduled](https://docs.unity3d.com/ScriptReference/AudioSource.PlayScheduled)