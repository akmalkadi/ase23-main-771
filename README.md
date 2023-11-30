# CodeT5-OCRfix: Improving Code Extraction from Coding Screencasts Using a Code-Aware Encoder-Decoder Model

## Abstract

Accurate automatic code extraction from tutorial videos is crucial for software developers seeking to reuse the code contained in these videos. Current methods using optical character recognition (OCR) often yield inaccurate results due to code complexity and variations in screencast formats. To address this issue, we introduce CodeT5-OCRfix, an approach that leverages the pre-trained code-aware large language model CodeT5 to enhance code extraction accuracy by post-processing OCRed code. We first collect a large and diverse dataset of source code screenshots captured from more than 10K Java projects from GitHub. We then apply the most widely used OCR engine for the task of code extraction from videos, Tesseract, on these screenshots and collect the OCRed code along with the ground truth code extracted from the Java files. We built a training dataset of more than 585K pairs of OCRed and ground truth code pairs, which we then used to fine-tune CodeT5, obtaining our model CodeT5-OCRfix. An empirical evaluation on both screenshots and screencast frames shows that CodeT5-OCRfix outperforms baseline code extraction models and is also more time-efficient. Our approach therefore improves the state-of-the-art in code extraction techniques from screencasts and images.

## Download

Access the replication package containing the CodeT5-OCRfix model, datasets, and associated resources through the following link:

[Download CodeT5-OCRfix Replication Package](https://99hf.short.gy/ase2023rep)

## Paper

Read the full research paper on IEEE Xplore:

[Improving Code Extraction from Coding Screencasts Using a Code-Aware Encoder-Decoder Model](https://ieeexplore.ieee.org/document/10298433)

## Citation

If you find our work useful, please consider citing our paper:

\[Malkadi, A., Tayeb, A., Haiduc, S. "Improving Code Extraction from Coding Screencasts Using a Code-Aware Encoder-Decoder Model." *38th IEEE/ACM International Conference on Automated Software Engineering (ASE)*, 2023\]

**BibTeX:**
```bibtex
@INPROCEEDINGS{10298433,
  author={Malkadi, Abdulkarim and Tayeb, Ahmad and Haiduc, Sonia},
  booktitle={2023 38th IEEE/ACM International Conference on Automated Software Engineering (ASE)}, 
  title={Improving Code Extraction from Coding Screencasts Using a Code-Aware Encoder-Decoder Model}, 
  year={2023},
  pages={1492-1504},
  doi={10.1109/ASE56229.2023.00184}
}
```

## Contact

For inquiries or further information, please contact the authors:

- Abdulkarim Malkadi
  - [Email](mailto:akmalkadi@jazanu.edu.sa)
  - Affiliation: Jazan University, Jizan, Jazan, Saudi Arabia
  - Affiliation: Florida State University, Tallahassee, FL, United States

- Ahmad Tayeb
  - [Email](mailto:tayeb@cs.fsu.edu)
  - Affiliation: Florida State University, Tallahassee, FL, United States

- Sonia Haiduc
  - [Email](mailto:shaiduc@cs.fsu.edu)
  - Affiliation: Florida State University, Tallahassee, FL, United States

Thank you for your interest in CodeT5-OCRfix!

