# Local-Global Self-Attention for Transformer-based Object Tracking (LGSAT)
Our Model Weight: [Baidu:vvw7](https://pan.baidu.com/s/131DRXutRF8bJpvTgVIj26g)  
Pretrain model: [TransT](https://drive.google.com/drive/folders/1GVQV1GoW-ttDJRRqaVAtLUtubtgLhWCE)  
Raw Result: [Baidu:5qry](https://pan.baidu.com/s/1k5n9qm55Bm1DqANlw_5LeA)  


![LGAST](noval.png)
![LGAST](pipline.png)

## Usage

### Installation  
Create and activate a conda environment, we've tested on this env: You can follow the env setting of [TransT](https://github.com/chenxin-dlut/TransT).   

### Data Preparation  
* RGB training datasets:  
  * [GOT-10K](http://got-10k.aitestunion.com/downloads)
  * [COCO](https://cocodataset.org/#home)
  * [LaSOT](https://pan.baidu.com/s/1UbcQIU-Fpps7Jqq4WHRRkA#list/path=%2FLaSOT%2Fzip)
  * [TrackingNet](https://github.com/SilvioGiancola/TrackingNet-devkit)

### Path Setting  
Following [TransT](https://github.com/chenxin-dlut/TransT)

### Testing  
```
python pysot_toolkit/test.py
```

## Citation  
```
@article{chena2024local,
  title={Local-Global Self-Attention for Transformer-Based Object Tracking},
  author={Chena, Langkun and Gaoa, Long and Jiangb, Yan and Lia, Yunsong and Hea, Gang and Ningc, Jifeng},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2024},
  publisher={IEEE}
}
```
