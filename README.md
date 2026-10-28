# 8-Class Shortwave Signal Dataset

Simulated HF (shortwave) communication signal dataset for classification research.

## Contents

- **8 classes**, **1000 samples each** (8000 total)
- **Format**: `float32` NumPy arrays, shape `(1000, 4096)` per class file
- **Sample rate**: 8000 Hz (0.512 s per sample)
- **Classes**: 2G-ALE, 3G-ALE BW0–BW4, CLOVER-2000, LINK11-CLEW

See `使用说明.txt` (Chinese) for loading examples, directory layout, and regeneration commands.

## Files

| File | Description |
|------|-------------|
| `*.npy` | Bulk waveforms per class |
| `manifest.json` | Generation metadata |
| `figures/` | Example waveforms and STFT plots |

## License

Add a license if you intend to share publicly.
