# datanextchallenge
The Datanext Noise Challenge: filter out noise in audio files to recreate the clean files.
Noise was filtered out with use of k means clustering. The audio files had 3 clusters of values: high values, low values and everything in between. We filtered out every value that belongs to the third cluster. 
The score was between 10 and 30% on files we tested ourselves.

In the repository you can find the code for our model, the model itself and the code to run on your audio file.
Run the code with the path to the file as command line argument. It returns an audio array and creates a new, denoised file (newfile.wav).

This code won the prize of originality.
