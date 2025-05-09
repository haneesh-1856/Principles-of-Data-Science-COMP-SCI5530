Emotion Recognition from Speech:
Introduction: One of the most basic forms of self-expression is speech, which encompasses a wide range of feelings, including excitement, peacefulness, joy, and rage, to mention a few. It is feasible to rearrange our activities, services, and even products in order to provide a more tailored experience to individual customers by evaluating the emotions that underlie communication.
Task: Create a classifier to recognize and extract emotions from different human voice sound files.

Data Link: https://drive.google.com/file/d/1wWsrN2Ep7x6lWqOXfr4rpKGYrJhWc8z7/view

Codebook for labels:

About Dataset
Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS) Speech audio-only files (16bit, 48kHz .wav) from the RAVDESS. Full dataset of speech and song, audio and video (24.8 GB) available from Zenodo. Construction and perceptual validation of the RAVDESS is described in our Open Access paper in PLoS ONE.

Files
This portion of the RAVDESS contains 1440 files: 60 trials per actor x 24 actors = 1440. The RAVDESS contains 24 professional actors (12 female, 12 male), vocalizing two lexically-matched statements in a neutral North American accent. Speech emotions includes calm, happy, sad, angry, fearful, surprise, and disgust expressions. Each expression is produced at two levels of emotional intensity (normal, strong), with an additional neutral expression.

File naming convention
Each of the 1440 files has a unique filename. The filename consists of a 7-part numerical identifier (e.g., 03-01-06-01-02-01-12.wav). These identifiers define the stimulus characteristics:

Filename identifiers
• Modality (01 = full-AV, 02 = video-only, 03 = audio-only).
• Vocal channel (01 = speech, 02 = song).
• Emotion (01 = neutral, 02 = calm, 03 = happy, 04 = sad, 05 = angry, 06 = fearful, 07 = disgust, 08 = surprised).
• Emotional intensity (01 = normal, 02 = strong). NOTE: There is no strong intensity for the 'neutral' emotion.
• Statement (01 = "Kids are talking by the door", 02 = "Dogs are sitting by the door").
• Repetition (01 = 1st repetition, 02 = 2nd repetition).
• Actor (01 to 24. Odd numbered actors are male, even numbered actors are female).
Filename example: 03-01-06-01-02-01-12.wav
1. Audio-only (03)
2. Speech (01)
3. Fearful (06)
4. Normal intensity (01)
5. Statement "dogs" (02)
6. 1st Repetition (01)
7. 12th Actor (12)
Female, as the actor ID number is even.

