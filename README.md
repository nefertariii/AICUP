## ReID 修改參數
### Solver
* MAX_EPOCH: 60 -> 80
* IMS_PER_BATCH: 512 -> 64
* GAMMA: 0.1 -> 0.2
* WEIGHT_DECAY: 0.0005 -> 0.00035
* WEIGHT_DECAY_NORM: 0.0005 -> 0.00035
* ETA_MIN_LR: 7.0e-07 -> 1.0e-07
* DELAY_EPOCHS: 30 -> 0
* CHECKPOINT_PERIOD: 20 -> 1
* BASE_LR: 0.00035 -> 0.0005
### Test
* EVAL_PERIOD: 20 -> 60
* IMS_PER_BATCH: 128 -> 256

## YOLOV7 修改參數  
### hyp
* iou_t: 0.20 -> 0.35
* scale: 0.5 -> 0.2
* shear: 0.0 -> 0.15
* perspective: 0.0 -> 0.0001
### opt
* epochs: 30 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # 自行設定為30，無初始值
* batch_size: 2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # 自行設定為2，無初始值
* img_size: 1280 * 1280&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # 自行設定為1280，無初始值
