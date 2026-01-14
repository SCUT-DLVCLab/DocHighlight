# DocHighlight: A Real-World Dataset for Document Specular Highlight Removal

[![Paper](https://img.shields.io/badge/Paper-PRCV%202025-red)](https://link.springer.com/chapter/10.1007/978-981-95-5676-2_8)
[![Method](https://img.shields.io/badge/Method-DocSHRNet-orange)](https://github.com/shallweiwei/DocSHRNet)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-green.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/) 

This repository contains the **DocHighlight dataset** for the paper [**"Towards Real-World Document Specular Highlight Removal: The DocHighlight Dataset and DocSHRNet Method"**](https://link.springer.com/chapter/10.1007/978-981-95-5676-2_8) published in *Pattern Recognition and Computer Vision (PRCV 2025)*.

**DocHighlight** is a large-scale, high-resolution dataset specifically designed for document specular highlight removal. The dataset comprises **2,201 rigorously aligned paired images** captured under diverse real-world conditions using a polarization-based acquisition pipeline, featuring:

- **Various document types**: books, magazines, receipts, and graphical content
- **Diverse illumination conditions**: varying color temperatures, brightness levels, and lighting angles
- **Multiple capture devices**: different camera types to ensure diversity
- **High resolution**: average 2924×3672 pixels (range: 1034×737 – 3468×4624)
- **Real-world highlights**: manual quality verification for reliable ground truth

The reference implementation **DocSHRNet** with training and inference code is available at 👉 [https://github.com/shallweiwei/DocSHRNet](https://github.com/shallweiwei/DocSHRNet).

---

## 📥 Download

The dataset is available via the following links:

- **[Baidu Netdisk](https://pan.baidu.com/s/1E_IFYcj72Is6OWJD7yi8CQ?pwd=doch)** 
- **[Quark Netdisk](https://pan.quark.cn/s/686b60514fa3)** 

---

## 📝 Usage Notes

- 🔒 **Non-commercial use only** ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)).  

---

## 📚 Citation

If this dataset is useful in your research or product, please cite our paper:

```bibtex
@InProceedings{10.1007/978-981-95-5676-2_8,
author="Xu, Haowei
and Zhang, Jiaxin
and Cheng, Hiuyi
and Zhang, Peirong
and Zheng, Xuhan
and Jin, Lianwen",
editor="Kittler, Josef
and Xiong, Hongkai
and Yang, Jian
and Chen, Xilin
and Lu, Jiwen
and Lin, Weiyao
and Yu, Jingyi
and Zheng, Weishi",
title="Towards Real-World Document Specular Highlight Removal: The DocHighlight Dataset and DocSHRNet Method",
booktitle="Pattern Recognition and Computer Vision",
year="2026",
publisher="Springer Nature Singapore",
address="Singapore",
pages="109--124",
abstract="Document images often suffer from specular highlights caused by reflective surfaces or uneven lighting conditions, which significantly compromise document readability and reduce optical character recognition (OCR) accuracy in camera-captured document images. However, current document specular highlight datasets face critical limitations such as low resolution, unrealistic synthetic highlights, and insufficient diversity, restricting their applicability to real-world scenarios. In addition, existing highlight removal methods are primarily designed for natural scenarios, which struggle to preserve fine-grained textual details and structural consistency required in real-world documents. To address these challenges, we first introduce DocHighlight, a high-resolution, real-world dataset specifically designed for document specular highlight removal. DocHighlight comprises 2,201 paired images captured under diverse conditions, featuring various document types, illumination settings, and capture devices. Subsequently, we propose Document Specular Highlight Removal Network (DocSHRNet), a new highlight removal method incorporating the Document Structure Attention (DSA) and Adaptive Receptive Field (ARF) modules. These modules facilitate precise structural preservation and adapt to multi-scale highlight patterns, ensuring high-quality restoration. Extensive experiments on the DocHighlight, RD, and SD1 datasets demonstrate that DocSHRNet delivers competitive performance in reconstruction quality and OCR accuracy. These results demonstrate the effectiveness of DocHighlight as a real-world dataset and the robustness of DocSHRNet in addressing document specular highlight removal challenges, providing a solid foundation for real-world applications. The dataset and code are publicly available at https://github.com/shallweiwei/DocSHRNet.",
isbn="978-981-95-5676-2"
}
```
