# FMFCC-V

FMFCC-V: A Large-Scale Challenging Asian Dataset for DeepFake Detection

## FMFCC-V Dataset

![FMFCC-V-Dataset](images/fig01.jpg)

The FMFCCV dataset is by far the first and the largest public available Asian dataset for DeepFake Detection. There are in total 38102 DeepFake videos and 44290 pristine videos, corresponding more than 23 million frames, in the FMFCC-V dataset. The source videos are collected from 83 paid individuals speaking in a variety of conditions for roughly 40 minutes each. All individuals are Asians and give consents to the use and manipulation of their faces by signing a formal agreement. The DeepFake videos are generated using four kinds of most popular face swapping methods for roughly 16 minutes each before post processing. In addition, we introduced diversity into both DeepFake videos and pristine videos through deliberate addition of twelve kinds of perturbations, simulating real world scenarios. Based on the FMFCC-V dataset and other existing DeepFake datasets, we benchmark video-level results of six representative DeepFake detection methods. The detailed analysis will be presented in a paper.

The complete FMFCC-V dataset can be download from https://pan.baidu.com/s/1wF87JgSbX_buqsc4eX-2FQ (Password: Data).

A part of FMFCC-V dataset can be downloaded from https://pan.baidu.com/s/1yaBcMP7ckvVI8KGf_Avk7Q (Password: 2021).

The structure of FMFCC-V dataset is:
```
FMFCC-V
|---Long_Version
|---|---fake
|---|---|---FMFCC-V+Long_Version+fake_part00.rar
|---|---|---FMFCC-V+Long_Version+fake_part01.rar
|---|---|---FMFCC-V+Long_Version+fake_part02.rar
|---|---|---FMFCC-V+Long_Version+fake_part03.rar
|---|---|---FMFCC-V+Long_Version+fake_part04.rar
|---|---|---FMFCC-V+Long_Version+fake_part05.rar
|---|---|---FMFCC-V+Long_Version+fake_part06.rar
|---|---|---FMFCC-V+Long_Version+fake_part07.rar
|---|---real
|---|---|---FMFCC-V+Long_Version+real_part00.rar
|---|---|---FMFCC-V+Long_Version+real_part01.rar
|---Short_Version
|---|---fake
|---|---|---FMFCC-V+Short_Version+fake_part00.rar
|---|---|---FMFCC-V+Short_Version+fake_part01.rar
|---|---|---FMFCC-V+Short_Version+fake_part02.rar
|---|---|---FMFCC-V+Short_Version+fake_part03.rar
|---|---|---FMFCC-V+Short_Version+fake_part04.rar
|---|---|---FMFCC-V+Short_Version+fake_part05.rar
|---|---|---FMFCC-V+Short_Version+fake_part06.rar
|---|---|---FMFCC-V+Short_Version+fake_part07.rar
|---|---|---FMFCC-V+Short_Version+fake_part08.rar
|---|---|---FMFCC-V+Short_Version+fake_part09.rar
|---|---|---FMFCC-V+Short_Version+fake_part10.rar
|---|---|---FMFCC-V+Short_Version+fake_part11.rar
|---|---|---FMFCC-V+Short_Version+fake_part12.rar
|---|---fake_aug
|---|---|---FMFCC-V+Short_Version+fake_aug_part00.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part01.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part02.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part03.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part04.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part05.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part06.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part07.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part08.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part09.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part10.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part11.rar
|---|---|---FMFCC-V+Short_Version+fake_aug_part12.rar
|---|---real
|---|---|---FMFCC-V+Short_Version+real_part00.rar
|---|---|---FMFCC-V+Short_Version+real_part01.rar
|---|---|---FMFCC-V+Short_Version+real_part02.rar
|---|---|---FMFCC-V+Short_Version+real_part03.rar
|---|---|---FMFCC-V+Short_Version+real_part04.rar
|---|---|---FMFCC-V+Short_Version+real_part05.rar
|---|---|---FMFCC-V+Short_Version+real_part06.rar
|---|---|---FMFCC-V+Short_Version+real_part07.rar
|---|---|---FMFCC-V+Short_Version+real_part08.rar
|---|---|---FMFCC-V+Short_Version+real_part09.rar
|---|---|---FMFCC-V+Short_Version+real_part10.rar
|---|---|---FMFCC-V+Short_Version+real_part11.rar
|---|---|---FMFCC-V+Short_Version+real_part12.rar
|---|---|---FMFCC-V+Short_Version+real_part13.rar
|---|---|---FMFCC-V+Short_Version+real_part14.rar
|---|---|---FMFCC-V+Short_Version+real_part15.rar
|---|---|---FMFCC-V+Short_Version+real_part16.rar
|---|---|---FMFCC-V+Short_Version+real_part17.rar
|---|---|---FMFCC-V+Short_Version+real_part18.rar
|---|---|---FMFCC-V+Short_Version+real_part19.rar
|---|---|---FMFCC-V+Short_Version+real_part20.rar
|---|---|---FMFCC-V+Short_Version+real_part21.rar
|---|---|---FMFCC-V+Short_Version+real_part22.rar
|---|---real_aug
|---|---|---FMFCC-V+Short_Version+real_aug_part00.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part01.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part02.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part03.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part04.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part05.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part06.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part07.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part08.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part09.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part10.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part11.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part12.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part13.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part14.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part15.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part16.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part17.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part18.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part19.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part20.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part21.rar
|---|---|---FMFCC-V+Short_Version+real_aug_part22.rar
```
For the real video of `001.mp4` in `FMFCC-V+Long_Version+real_part00.rar`:
```
001: index of real video
```
For the fake video of `014_006_007.mp4` in `FMFCC-V+Long_Version+fake_part00.rar`:
```
014: index of fake video
006: index of target video of fake video 014
007: index of source video of fake video 014
```
For the real video of `001_003.mp4` in `FMFCC-V+Short_Version+real_part00.rar` and `FMFCC-V+Short_Version+real_aug_part00.rar`:
```
001: index of real video
003: number of real video 001
```
For the fake video of `002_001_006_081.mp4` in `FMFCC-V+Short_Version+fake_part00.rar` and `FMFCC-V+Short_Version+fake_aug_part00.rar`:
```
002: index of fake video
001: index of target video of fake video 002
006: index of source video of fake video 002
081: number of fake video 002
```
The structure of a part of FMFCC-V dataset used in the FMFCC-V competition is:
```
FMFCC-V-Competition
|---metadata.json
|---videos_30000_part1.zip
|---videos_30000_part2.zip
|---videos_30000_part3.zip
|---videos_30000_part4.zip
```

## FMFCC-V Competition

![FMFCC-V-Competition](images/fig02.jpg)

Based on the FMFCC-V dataset, we have successfuly hosted a benchmark competition named Video track of the first Fake Media Forensic Challenge of China Society of Image and Graphics (FMFCC-V). The FMFCC-V competition attracted over 400 contestants who come from 60 organizations. The monetary prizes provided a large incentive for these contestants to dedicate a lot of time and computational resources to optimize DeepFake detection algorithms for benchmarking. Compared with the DFDC competition organized by FaceBook, we only gather the metadata of predictions rather than the source codes and models for protecting the intellectual property rights of the contestants. Based on the result of the FMFCC-V competition, we provided a detailed analysis of top submissions. The details will be presented in a paper.

The homepage of FMFCC-V competition is http://fmfcc.net.

## Acknowledgements

If you use the FMFCC-V dataset, please cite the following paper:
```
@inproceedings{XXX,
  title = {FMFCC-V: A Large-Scale Challenging Asian Dataset for DeepFake Detection},
  author = {Gen Li, Xianfeng Zhao, Yun Cao, Pengfei Pei, Jinchuan Li, Zeyu Zhang},
  booktitle = {XXX},
  year = {2021}
}
```
or cite the online document:
```
@online{XXX,
  title = {FMFCC-V: A Large-Scale Challenging Asian Dataset for DeepFake Detection},
  author = {Gen Li, Xianfeng Zhao, Yun Cao, Pengfei Pei, Jinchuan Li, Zeyu Zhang},
  url = {https://github.com/iiecasligen/FMFCC-V/},
  year = {2021}
}
```
