# The world's simplest musical instrument classifier, using Constant-Q Transform and Logistic Regression.

This Jupyter Notebook regards how to pre-process an audio recording dataset, slicing all musical instrument samples in one second duration samples, transforms them in a time-frequency representation with Constant-Q Transform (CQT), to finally train a simple logistic regression classifier.

All these samples were taken from University of Iowa Electronic Music Studios: http://theremin.music.uiowa.edu/MIS.html

The samples includes single-notes recorded these instruments:
- Alto Saxophone, without vibrato
- Soprano Saxophone, without vibrato (Soprano sounds higher than Alto)
- Flute, without vibrato
- Horn (Trompa)
- Marimba, played with rubber, chord and yarn mallet, some of them with deadstroke.
- Bell, played with plastic and brass mallet
- Violin, with arco and pizzicato (from the samples I heard, without vibrato, but not explicit in their website)
- Viola, with arco and pizzicato (same condition as Violin)

at July 5th, 2020, these were the results:

              precision    recall  f1-score   support

     AltoSax       0.64      0.52      0.57        95
       Bells       0.74      0.60      0.66       131
       Flute       0.66      0.68      0.67        59
        Horn       0.87      0.80      0.83        59
     Marimba       0.86      0.74      0.79        42
      SopSax       0.33      0.58      0.42        12
       Viola       0.74      0.62      0.68        96
      Violin       0.85      0.93      0.89       611

    accuracy                           0.80      1105
    macro avg      0.71      0.68      0.69      1105
    weighted avg   0.79      0.80      0.79      1105
