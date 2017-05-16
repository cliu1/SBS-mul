# SBS-mul

This is a forked repo experimented during 2015 JHU Workshop and published in icassp 16. 
Outdated. Please find the latest in https://github.com/uiuc-sst/PTgen.


Usage:

```
git clone https://www.github.com/kaldi-asr/kaldi;
cd kaldi/egs;
git clone https://www.github.com/ws15code/SBS-mul;
cd SBS-mul;
ln -s ../wsj/s5/steps steps;
ln -s ../wsj/s5/utils utils;
qsub -cwd ./run.sh;
```
