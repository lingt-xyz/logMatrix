# logMatrix
metrics of output from ml

## Output

A CSV file is to be expected.

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