# SLTD Dataset: Tailored for Small Liver Tumor Detection

This dataset is designed specifically for detecting **small liver tumors** from contrast-enhanced CT scans. It accompanies our paper:

📄 [**"PCA-YOLO: A Small Liver Tumor Detection Model with Patch-Contrastive Attention"** (MIDL 2025)](https://openreview.net/pdf?id=iEBZjNZ63T)

---

## 🧠 Why This Dataset

Existing segmentation datasets (e.g., LiTS) are not optimized for tumor **detection**:

- Bounding boxes converted from segmentation masks are often ambiguous, especially for small or adjacent tumors.
- Most segmentation datasets include easy slices; this dataset emphasizes challenging small-lesion cases.
- Bounding box annotation is faster and more clinically aligned than segmentation masks.

---

## 📁 What's Included

- Selected CT slices focused on small liver tumors
- Expert-annotated bounding boxes
- Serves as a benchmark for small object detection tasks

---

## 🔗 Download

[Download the dataset](https://drive.google.com/drive/folders/11Um7nUdTTOzUqBtl2eO1Iq5ky9xTFkqH?usp=drive_link)

---

## 📌 Citation

If you use this dataset, please cite:

```bibtex
@inproceedings{
  li2025pcayolo,
  title={{PCA}-{YOLO}: A Small Liver Tumor Detection Model with Patch-Contrastive Attention},
  author={Xueyang Li and Han Xiao and Zongpeng Weng and Xinrong Hu and Danny Chen and Yiyu Shi},
  booktitle={Medical Imaging with Deep Learning},
  year={2025},
  url={https://openreview.net/forum?id=iEBZjNZ63T}
}
