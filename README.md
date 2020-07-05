# The world's simplest instrument classifier, using Constant-Q Transform and Logistic Regression.

This Jupyter Notebook regards how to pre-process an audio recording dataset, slicing all audios in one second duration samples, transforms them in a time-frequency representation with Constant-Q Transform (CQT), to finally train a simple logistic regression classifier.

All these samples were taken from University of Iowa Electronic Music Studios: http://theremin.music.uiowa.edu/MIS.html
The samples includes:
- Alto Saxophone, without vibrato
- Soprano Saxophone, without vibrato (Soprano sounds higher than Alto)
- Flute, without vibrato
- Horn (Trompa)
- Marimba, played with rubber, chord and yarn mallet, some of them with deadstroke.
- Bell, played with plastic and brass mallet
- Violin, with arco and pizzicato (from the samples I heard, without vibrato, but not explicit in their website)
- Viola, with arco and pizzicato (same condition as Violin)
