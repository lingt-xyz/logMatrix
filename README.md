# logMatrix
metrics of output from ml

## Input

log file of the format:

```
Epoch 1/33
798/798 [==============================] - 6341s 8s/step - loss: 2.7144 - accuracy: 0.4629 - val_loss: 2.0714 - val_accuracy: 0.4864
Epoch 2/33
798/798 [==============================] - 6511s 8s/step - loss: 2.1010 - accuracy: 0.5019 - val_loss: 1.8767 - val_accuracy: 0.4864
```
## Output

A CSV file with the columns:

```
epoch,total time,time per step,loss,accuracy,val_lost,val_accuracy
```

File name will be the name of the input file appends with `.csv`

## How to run it

```shell script
./logMatrix -input=FILE_NAME
```

- `-input=` accepts a log file name.

e.g.:


```shell script
./logMatrix -input=seq2seq.txt
```

- Input file is `seq2seq.txt`
- Output file is `seq2seq.txt.csv`