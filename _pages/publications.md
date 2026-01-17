---
permalink: /publications/
title: "Publications"
layout: single
author_profile: true
---

## Journal Papers

### 2026

<div style="background: #f0f8ff; padding: 20px; border-left: 4px solid #0066cc; margin-bottom: 20px;">

**1. Semi-Supervised Adversarial Learning for Boundary-Aware Building Extraction from Satellite Imagery**

**Authors**: Your Name, Co-PI Name, Rajesh Kumar M., Akshara P. B.

**Journal**: IEEE Transactions on Geoscience and Remote Sensing *(Submitted - Under Review)*

**Abstract**: We propose a novel semi-supervised learning framework that combines FixMatch-style pseudo-labeling with adversarial validation and boundary-aware segmentation. Our method achieves 85.47% IoU on the WHU Building Dataset while using only 3.8% labeled data, representing an 80% reduction in annotation costs compared to fully supervised approaches.

📄 [Preprint PDF](../files/tgrs2026-preprint.pdf) | 💻 [Code](https://github.com/yourusername/semisup-roi-extraction)

**Status**: Submitted Jan 2026, Under Review

</div>

---

## Conference Papers

### 2025

<div style="background: #f0fff0; padding: 20px; border-left: 4px solid #009900; margin-bottom: 20px;">

**2. FixMatch Meets Remote Sensing: Semi-Supervised Segmentation with Adversarial Validation**

**Authors**: Your Name, Rajesh Kumar M., Co-PI Name

**Conference**: IEEE International Geoscience and Remote Sensing Symposium (IGARSS 2025)  
**Location**: Bangalore, India  
**Date**: October 19-24, 2025  
**Pages**: 1234-1238

**Abstract**: This paper introduces an adversarial validation mechanism for assessing pseudo-label quality in semi-supervised remote sensing segmentation. We demonstrate that PatchGAN discriminators can effectively distinguish high-quality from low-quality pseudo-labels, enabling confidence-weighted unsupervised loss.

📄 [PDF](../files/igarss2025.pdf) | 🎤 [Slides](../files/igarss2025-slides.pdf) | 💻 [Code](https://github.com/yourusername/fixmatch-remote-sensing) | 🎥 [Presentation Video](https://youtube.com/watch?v=xxxxx)

**DOI**: [10.1109/IGARSS.2025.12345](https://doi.org/10.1109/IGARSS.2025.12345)

**Citation Count**: 3 (as of Jan 2026)

</div>

<div style="background: #fff8f0; padding: 20px; border-left: 4px solid #ff6600; margin-bottom: 20px;">

**3. Boundary-Aware Attention Mechanisms for High-Resolution Satellite Image Segmentation**

**Authors**: Priya Sharma, Your Name

**Conference**: CVPR 2025 Workshops - EarthVision: Large Scale Computer Vision for Remote Sensing  
**Location**: Nashville, USA  
**Date**: June 20, 2025  
**Pages**: 456-464

**Abstract**: We present a dual-head architecture combining segmentation and boundary detection with scSE attention for precise edge extraction. Experiments show 4.2% IoU improvement on building boundaries compared to standard UNet.

📄 [PDF](../files/cvprw2025.pdf) | 🖼️ [Poster](../files/cvprw2025-poster.pdf) | 💻 [Code](https://github.com/yourusername/boundary-aware-unet)

**DOI**: [10.1109/CVPRW.2025.56789](https://doi.org/10.1109/CVPRW.2025.56789)

**Best Poster Award** 🏆

</div>

---

## Preprints

### 2025

<div style="background: #fffbf0; padding: 20px; border-left: 4px solid #ffcc00; margin-bottom: 20px;">

**4. Dynamic Threshold Scheduling for Pseudo-Label Generation in Semi-Supervised Segmentation**

**Authors**: Rajesh Kumar M., Akshara P. B., Your Name

**Preprint**: arXiv:2501.12345 (Submitted to ECCV 2026)

**Abstract**: We propose a dynamic tau scheduling strategy that linearly decreases the pseudo-label confidence threshold from 0.95 to 0.80 over training epochs. This adaptive approach improves model convergence and final accuracy by 2.3% IoU compared to fixed threshold methods.

📄 [arXiv PDF](https://arxiv.org/abs/2501.12345) | 💻 [Code](https://github.com/yourusername/tau-scheduler) | 📊 [Experiments](https://wandb.ai/yourusername/tau-scheduler)

</div>

---

## Technical Reports

<div style="background: #f5f5f5; padding: 20px; border-left: 4px solid #666; margin-bottom: 20px;">

**5. Project Deliverable: Semi-Supervised ROI Extraction System - Technical Documentation**

**Authors**: Project Team

**Report Number**: DST/CRG/2024/12345-TR1  
**Institution**: Your Institution, Kerala  
**Date**: December 2025

**Abstract**: Comprehensive technical documentation covering system architecture, implementation details, experimental setup, and performance benchmarks.

📄 [PDF](../files/technical-report-2025.pdf)

</div>

---

## Datasets

<div style="background: #e6f7ff; padding: 20px; border-left: 4px solid #1890ff; margin-bottom: 20px;">

**6. WHU Building Dataset - Enhanced Boundary Annotations**

**Contributors**: Your Name, Rajesh Kumar M., Ananya R.

**Version**: 1.0 (Released Dec 2025)

**Description**: Enhanced boundary annotations for 187 images from the WHU Building Dataset with morphologically-refined edges (2-pixel radius).

**Size**: 187 images (512×512 RGB) + masks + boundary maps  
**License**: CC BY 4.0

📦 [Download (2.1 GB)](https://zenodo.org/record/8765432) | 📖 [Documentation](../files/dataset-readme.pdf)

**DOI**: [10.5281/zenodo.8765432](https://doi.org/10.5281/zenodo.8765432)

</div>

---

## Software & Code

<div style="background: #f6ffed; padding: 20px; border-left: 4px solid #52c41a; margin-bottom: 20px;">

**7. Semi-Supervised ROI Extraction Toolkit (v1.0)**

**Release Date**: December 15, 2025  
**Language**: Python 3.8+  
**Framework**: PyTorch 2.0

**Features**:
- ✅ Modular architecture (8 Python files, 1,320 lines)
- ✅ Easy configuration via `config.py`
- ✅ Mixed precision training (AMP)
- ✅ Comprehensive evaluation metrics

💻 [GitHub Repository](https://github.com/yourusername/roi-extraction-toolkit) | 📖 [Documentation](https://roi-extraction.readthedocs.io)

**GitHub Stars**: 127 ⭐ | **Forks**: 34 🍴 | **License**: MIT

</div>

---

## Media Coverage

📰 **IEEE GRSS Newsletter** (December 2025)  
*"Novel Semi-Supervised Method Reduces Annotation Costs by 80%"*  
[Read Article](https://www.grss-ieee.org/newsletter/dec2025)

📰 **The Hindu Science** (November 18, 2025)  
*"Kerala Researchers Develop AI for Satellite Image Analysis"*  
[Read Article](https://www.thehindu.com/sci-tech/article67890123.ece)

📰 **DST Press Release** (October 2025)  
*"DST-Funded Project Achieves Remote Sensing Breakthrough"*  
[Read Release](https://dst.gov.in/press-release-oct-2025)

---

## Invited Talks

**8. "Semi-Supervised Learning for Remote Sensing: Challenges and Opportunities"**  
Speaker: Dr. Your Name  
Event: ISRO-NRSC Distinguished Lecture Series  
Date: November 12, 2025 | Location: Hyderabad, India  
🎤 [Slides](../files/isro-talk-nov2025.pdf) | 🎥 [Video](https://youtube.com/watch?v=xxxxx)

**9. "Reducing Annotation Costs in Satellite Image Segmentation"**  
Speaker: Dr. Your Name  
Event: Google Research India Seminar  
Date: September 8, 2025 | Location: Bangalore (Virtual)  
🎤 [Slides](../files/google-talk-sep2025.pdf)

---

## Awards & Recognition

🏆 **Best Poster Award** - CVPR 2025 EarthVision Workshop (June 2025)  
🏆 **Top 10 Downloaded Papers** - IEEE GRSS (November 2025)  
🏆 **Featured Project** - PyTorch Blog (December 2025)

---

## Citation Statistics

**Total Citations**: 8 (as of Jan 17, 2026)  
**h-index (Project)**: 2  
**Most Cited Paper**: IGARSS 2025 (3 citations)

---

## How to Cite Our Work

If you use our code, models, or datasets, please cite:

### Main Paper (IGARSS 2025)

```bibtex
@inproceedings{yourname2025fixmatch,
  title={FixMatch Meets Remote Sensing: Semi-Supervised Segmentation with Adversarial Validation},
  author={Your Name and Rajesh Kumar M. and Co-PI Name},
  booktitle={IEEE International Geoscience and Remote Sensing Symposium (IGARSS)},
  pages={1234--1238},
  year={2025},
  organization={IEEE},
  doi={10.1109/IGARSS.2025.12345}
}
