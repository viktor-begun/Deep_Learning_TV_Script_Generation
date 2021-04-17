# TV-Script-Generation

This project is a part of my [Deep Learning](https://www.udacity.com/course/deep-learning-nanodegree--nd101) Nanodegree from [Udacity](https://www.udacity.com/), see the [Completion Certificate](https://graduation.udacity.com/confirm/QCK3UKSS).

In this project, I generate my own [Seinfeld](https://en.wikipedia.org/wiki/Seinfeld) TV scripts using Recurrent neural network (RNN). I use a part of the [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) of scripts from 9 seasons.  The Neural Network which I build generates a new ,\"fake\" TV script, based on patterns it recognizes in this training data.

**Example generated script:**

`prime_word = 'john' # name for starting the script`

john: machines, and you know, i don't think you might be a man.

puddy: oh yeah yeah.

jerry: i don't wanna do that. it's not a joke.

george: well, what happened to you, i had to go to your party, but i was thinking about the whole thing.

george: oh, yeah. i don't know.

puddy:(standing up and smiles) so how do you have a good meal?

See the complete solution in the [my_dlnd_tv_script_generation.ipynb](https://github.com/viktor-begun/Deep_Learning_TV_Script_Generation/blob/main/my_dlnd_tv_script_generation.ipynb) file.

Libraries and methods used: `torch:`, `TensorDataset`, `DataLoader`, `torch.nn`, `torch.nn.functional`; `NumPy`, `collections.Counter`, `unittest`.
