# What I learned when trying to transcribe an audio file with Python

Once a month I attended a meeting at my Department to discuss issues related to the Chemistry Undergraduate Course. An audio of the meeting is recorded with the help of a mobile phone, and later the secretary writes the respective minutes that are then filed after being approved by the participants. In general, the recording time is about 2 hours long and there are eight participants who speak Brazilian Portuguese and have different accents.

In an attempt to automate the transcription of this audio (named meeting.wav) and to make it one of my adventures with Python, I decided to use Python to get this job done.

The quality of the transcribed text is far from reality. The audio used was registered using a mobile phone, so it doesn't have a high quality. However, I believe that the greatest difficulty in transcription was caused by the way of speaking of the participants who speaks with different accents and dialects or speak very fast and don't separate words and sentences what makes their speech unclear to the engine, without using a more sophisticated and trained algorithm. Many other factors like age, gender, context, intent, etc, also can affect the recognition process.

Human speech is not a simple phenomenon and it is influenced by many complex factors that are constantly changing as we change who speak. Machine recognition systems work much better in ideal conditions where we can reduce noise levels and the speeach is paced. Fortunately, there are algorithms and techniques more sophisticated to tackle this problem but this is not the subject here.


Libraries used in this project:
* `speech_recognition`
* `os`
* `pydub`
