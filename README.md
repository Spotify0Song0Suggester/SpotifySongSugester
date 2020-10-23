# SpotifySongSugester

This web application takes in user input to create song suggestions. The user types a song name and the model returns similar songs based on output.

To return the output, there are actually two models. Both models ran sklearn's NearestNeighbors algorithm. The first model is trained solely on the vecotrized song names in order to recognize the user input. The output of that first model returns songs of names most similar to the user input. 
The user then chooses the song most similar to their input and then that is used as the input for the second model which returns the song suggestions based on various similarities in sound characteristics of the song.

However the model was trained on a small subset of the entire dataset so the output is limited.

