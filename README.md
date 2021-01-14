## Training

Download [COCO](https://github.com/ultralytics/yolov3/blob/master/data/scripts/get_coco.sh) and run command below. Training times for YOLOv3/YOLOv3-SPP/YOLOv3-tiny are 6/6/2 days on a single V100 (multi-GPU times faster). Use the largest `--batch-size` your GPU allows (batch sizes shown for 16 GB devices).
```bash
$ python train.py --data coco.yaml --cfg yolov3.yaml --weights '' --batch-size 24
                                         yolov3-spp.yaml                       24
                                         yolov3-tiny.yaml                      64
```
<img src="https://user-images.githubusercontent.com/26833433/100378028-af170c80-3012-11eb-8521-f0d2a8d021bc.png" width="900">


## Citation

[![DOI](https://zenodo.org/badge/146165888.svg)](https://zenodo.org/badge/latestdoi/146165888)


## About Us

Ultralytics is a U.S.-based particle physics and AI startup with over 6 years of expertise supporting government, academic and business clients. We offer a wide range of vision AI services, spanning from simple expert advice up to delivery of fully customized, end-to-end production solutions, including:
- **Cloud-based AI** systems operating on **hundreds of HD video streams in realtime.**
- **Edge AI** integrated into custom iOS and Android apps for realtime **30 FPS video inference.**
- **Custom data training**, hyperparameter evolution, and model exportation to any destination.

For business inquiries and professional support requests please visit us at https://www.ultralytics.com. 


## Contact

**Issues should be raised directly in the repository.** For business inquiries or professional support requests please visit https://www.ultralytics.com or email Glenn Jocher at glenn.jocher@ultralytics.com. 
