# SPLG-Mamba Prediction Maps

This package provides the saliency prediction maps of **SPLG-Mamba** on three optical remote-sensing salient object detection benchmarks.

## Contents

```text
SPLG-Mamba_prediction_maps/
├── ORSSD/      # 200 prediction maps
├── EORSSD/     # 600 prediction maps
└── ORS-4199/   # 2199 prediction maps
```

The file names follow the corresponding test images and ground-truth masks in each dataset. All maps are stored as grayscale PNG saliency maps.

## Usage

These maps are shared for reproducible comparison and academic research. They can be evaluated with standard SOD metrics such as MAE, S-measure, weighted F-measure, maximum F-measure, E-measure, and mean F-measure.

## Citation

If these prediction maps are useful for your research, please cite our paper:

```bibtex
@misc{splg_mamba,
  title  = {SPLG-Mamba: Structure-Preserving Local-Global Mamba Network for Salient Object Detection in Optical Remote Sensing Images},
  author = {Xu, Yi and Hou, Ruichao and Ren, Tongwei and Wu, Gangshan},
  year   = {2026},
  note   = {Manuscript under review}
}
```

## Contact

For questions, please contact Yi Xu at `yxu1025@smail.nju.edu.cn`.
