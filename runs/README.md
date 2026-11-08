# Training Results

This folder contains the training outputs from all hyperparameter tuning experiments.

## Folder Structure

### Baseline
- `baseline_adamw/` - Baseline model (epochs=5, batch=8, lr0=0.0005, optimizer=AdamW, imgsz=640)

### Michelle - Learning Rate
- `lr_0.0001_adamw/` - Learning rate = 0.0001 (best, mAP50-95: 0.641)
- `lr_0.001_adamw/` - Learning rate = 0.001
- `lr_0.005_adamw/` - Learning rate = 0.005

### Yumin - Epochs
- `epochs_10_adamw/` - Epochs = 10
- `epochs_20_adamw/` - Epochs = 20 (best overall, mAP50-95: 0.665)
- `epochs_30_adamw/` - Epochs = 30

### Nicole - Batch Size
- `batch_4_adamw/` - Batch size = 4 (best, mAP50-95: 0.648)
- `batch_16_adamw/` - Batch size = 16
- `batch_30_adamw/` - Batch size = 30

### Zainab - Image Size
- `imgsz_416_adamw/` - Image size = 416
- `imgsz_512_adamw/` - Image size = 512 (best, mAP50-95: 0.639)
- `imgsz_800_adamw/` - Image size = 800

### Test Set Evaluation
- `test_evaluation/` - Final model evaluation on 122 test images

## Note
Model weights (.pt files) are not included in this repository due to file size limitations.
