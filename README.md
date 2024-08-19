# SPA (Sight Player AI)

This project aims to implement a generative AI, comprised of a convolutional neural network and variational recurrent neural network, to create new music by reconstructing user-provided music. 

The model intakes a .midi file of instrumental, converts it to a piano roll, then uses the piano roll to train. The model will then output a reconstructed piano roll which is converted back to a .midi file. This means that the model's generated music will be played a piano.


## Installation
Use Python 3.11.9 and create a virtual environment. Then, run the below command to install the necessary packages:

```
pip install -r requirements.txt
```

## Running the Project
Acquire a .midi file of your desired instrumental. Next, update the `input_song` and `input_song_path` variables with the .midi file's name and path. Then, run the notebook!

## Issues
1. I'm using an ancient version of Tensorflow! An update is hopefully on the way! 🙏  

2. The model's outputted music is only ever played by a piano. 
