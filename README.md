# text-cnn
Tensorflow FULL Implementation of Yoon Kim's Text CNN Paper

### Director: BOSS Li (Chris Li)
#### Experiment design and report: Shenshun Yao
#### Code: Yuxiang Ma

## Requirement
1. numpy
2. gensim
3. tensorflow
4. tensorboard

## Repeat of Experiment
1. Specify Location of data files
```
to_trainer = TOTrainParameter(
    '/content/gdrive/My Drive/cs551final/data'
)
```
2. Make a dirctory "W2V" under "data", and put google w2v bin file under it. 
3. Run utility functions and class models by "Runtime" -> "Run Before" on "Before Running your section, do a "Runtime" -> "Run before" on previous cells." cell. 

4. choose your experiment to run. 

## Reference
Code Base was imported from https://github.com/dennybritz/cnn-text-classification-tf, with significant modifications to adapt the actual paper. 
