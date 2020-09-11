# CRVOS: Clue Refining Network for Video Object Segmentation

[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/crvos-clue-refining-network-for-video-object/visual-object-tracking-on-davis-2016)](https://paperswithcode.com/sota/visual-object-tracking-on-davis-2016?p=crvos-clue-refining-network-for-video-object)

#### Suhwan Cho, MyeongAh Cho, Tae-young Chung, Heansung Lee, Sangyoun Lee


---
### Download
[[arXiv_paper]](https://arxiv.org/pdf/2002.03651v4.pdf)


[[DAVIS 2017]](https://davischallenge.org/davis2017/code.html)


[[pre-trained model]](https://drive.google.com/file/d/1ypjAb_cacM1zPILUFdXY1R-fRPWfXEzi/view?usp=sharing)


[[pre-computed results]](https://drive.google.com/file/d/193e3BMFEYdiWwT9pJ8eU8ohhHhn0CKlG/view?usp=sharing)


---
### Usage
1. Modify 'davis_path' in 'local_config.py'.

2. Check fps.
```
python test.py --fps
```

3. Save the results.
```
python test.py --save
```

---
### Others
DAVIS_2016.txt, DAVIS_2017.txt, DAVIS_fps.txt: Accuracies and speeds on DAVIS datasets.

We use a single GeForce RTX 2080 Ti GPU.


---
### Citation
```
@article{cho2020crvos,
  title={CRVOS: Clue Refining Network for Video Object Segmentation},
  author={Cho, Suhwan and Cho, MyeongAh and Chung, Tae-young and Lee, Heansung and Lee, Sangyoun},
  journal={arXiv preprint arXiv:2002.03651},
  year={2020}
}
```

---
### Acknowledgement
This code is built on [joakimjohnander/agame-vos](https://github.com/joakimjohnander/agame-vos).
