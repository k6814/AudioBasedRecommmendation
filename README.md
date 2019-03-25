# AudioBased Recommendation

Approach:-
Step1:-Converts the mp3 to wav. 

Step2:-The wav file is then converted to a spectogram image

Step 3:-Resize spectogram image size to 128 by 128 image size.

Step 4:- Training is done using Autoencoder nueral network on the images. Each song is represented by a vector, which is of size 128 x 128 x 3. 3 for 3 channels (r,g,b)

Step 5:-Calculated euclidean distance matrix of the song vectors

Step 6:- Recommend users songs based on the Euclidean Distance.


