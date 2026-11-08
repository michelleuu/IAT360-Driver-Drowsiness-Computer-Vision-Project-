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
- `test_predictions/` - Prediction visualizations on test images

## Key Files in Each Folder
- `args.yaml` - Training configuration
- `results.csv` - Per-epoch training metrics
- `results.png` - Training curves
- `confusion_matrix_normalized.png` - Normalized confusion matrix
- `weights/best.pt` - Best model weights (only in epochs_20_adamw)
