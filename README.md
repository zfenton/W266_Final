### DATASCI266 - Natural Language Processing
*Final Project - Section 002*

__Alec Naidoo, Zachary Fenton__

#### Automating the Bechdel Test ####

The Bechdel Test is a simple test for checking the bias of a movie. It has three rules that need to be met to pass the test:

1. The movie must contain at least two __named__ female characters.
2. Two of the named female characters need to speak with eachother.
3. They must speak about something other than a man.

The Bechdel test was originally created by Alison Bechdel. It appeard in a comic stop titled "The Rule" that was published in 1985. A great article on the test can be found [here](https://lithub.com/read-the-1985-comic-strip-that-inspired-the-bechdel-test/).

Our paper can be found [here](https://github.com/zfenton/W266_Final/blob/main/Automatic%20Bechdel.pdf)

In the [coref_submit](https://github.com/zfenton/W266_Final/tree/main/coref_submit) folder is the code for the Coreference Resolution model approach, specifically in [this](https://github.com/zfenton/W266_Final/blob/main/coref_submit/poetry-mica-char-coref/241113_experiment.ipynb) notebook.

In the [screenplayparser](https://github.com/zfenton/W266_Final/tree/main/screenplayparser) folder, you can find the raw files for parsing screenplays. To run them, use [parser_run.ipynb](https://github.com/zfenton/W266_Final/blob/main/parser_run.ipynb)

Raw data - [Link](https://huggingface.co/datasets/mocboch/movie_scripts/tree/main)

Screenplay parser original work is from [__sabyasachee__](https://github.com/usc-sail/mica-screenplay-parser/tree/main). Parser is missing the model.pt file for pre-trained model weights. It can be downloaded [here](https://github.com/usc-sail/mica-screenplay-parser/tree/main/screenplayparser)
