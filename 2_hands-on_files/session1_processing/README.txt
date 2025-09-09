We provided raw data from two publicly available data sets:


DATASET 1: RAVDESS; https://doi.org/10.5281/zenodo.1188975

The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)

This contains English video and audio from actors speaking select sentences with different emotional expressions.

Each of the 7356 RAVDESS files has a unique filename. The filename consists of a 7-part numerical identifier (e.g., 02-01-06-01-02-01-12.mp4). These identifiers define the stimulus characteristics: 

Filename identifiers 

Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
Vocal channel (01 = speech, 02 = song).
Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.
Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").
Repetition (01 = 1st repetition, 02 = 2nd repetition).
Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).

Filename example: 02-01-06-01-02-01-12.mp4 

Video-only (02)
Speech (01)
Fearful (06)
Normal intensity (01)
Statement "dogs" (02)
1st Repetition (01)
12th Actor (12)
Female, as the actor ID number is even.


DATASET 2: EMO-DB; https://www.kaggle.com/datasets/piyushagni5/berlin-database-of-emotional-speech-emodb?resource=download

Berlin Database of Emotional Speech (EMO-DB)

This contains German audio from actors speaking select sentences with different emotional expressions.

Every utterance is named according to the same scheme:

Positions 1-2: number of speaker
Positions 3-5: code for text
Position 6: emotion (sorry, letter stands for german emotion word)
Position 7: if there are more than two versions these are numbered a, b, c ....
Example: 03a01Fa.wav is the audio file from Speaker 03 speaking text a01 with the emotion "Freude" (Happiness).

                     
