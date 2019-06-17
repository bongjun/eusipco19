# dcase-17 dataset for (Weakly) Supervised Attention models

This repository contains a list of YouTube IDs from a subset of Google's [AudioSet](https://research.google.com/audioset/) which has been used to evaluate a new attention model of our recent submission to a conference. We will add more details informaiton about the model upon acceptance.

Our model takes both strongly-labeled and weakly-labeled training examples. To evaluate models in both cases, we need a dataset with both weak and strong labels. Therefore, we collected strongly-labeled dataset from evaluation and testing set of [DACSE17-task4 challange](http://www.cs.tut.fi/sgn/arg/dcase2017/challenge/task-large-scale-sound-event-detection) which is also a subset of AudioSet. DCASE17 set only has 17 classes of audio events. The classes are Train horn, Air horn, truck horn, Car alarm, Reversing beeps, Ambulance, Police car (siren), Fire truck (siren), Civil defense siren, Screaming. This repository contains YouTube IDs that we used for our training and evaluation. 

There are three files in the repository.

* train_strong_labels.csv (tab-delimited): It contains file names with strong labels of training set. Strong labels were collected from testing set and evaluations of DCASE17 challange task4. You can download the audio files from the [DCASE challange page](http://www.cs.tut.fi/sgn/arg/dcase2017/challenge/task-large-scale-sound-event-detection). The csv file format is the same as ones released from the challange.

* validation_set.csv (tab-delimited): It contains YouTube IDs with weak labels of validation set for training. This list was collected from unblanced train data of AudioSet. The csv file format is the same as the original one released by Google which you can download in [its official page](https://research.google.com/audioset/download.html) 

* test_set.csv (tab-delimted): It conatins YouTube IDs with weak labels of testing set. This list was collected from balanced evaluation set of AudioSet. The csv file format is the same as the original one released by Google which you can download in [its official page](https://research.google.com/audioset/download.html)

