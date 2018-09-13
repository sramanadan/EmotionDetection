VokaMono for Android sample code

This code requires a Vokaturi SDK .aar file in the folder app/libs.

Audio data is captured from the microphone via OnRecordPositionUpdateListener.
A number of activities are ties to the listener via the UpdatableActivity interface.
Every numOfSamples emotion data is extracted.
When data is extracted every UpdatableActivity receives the emotion object via and displays it accordingly.

