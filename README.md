# PEPR: Privileged Event-based Predictive Regularization for Domain Generalization

[![paper](https://img.shields.io/badge/paper-CVPRF26-blue.svg)](https://arxiv.org/pdf/2602.04583)

<div align="center">
  <img src="https://github.com/miccunifi/PEPR/blob/main/static/images/stage_true.pdf?raw=true" 
     alt="PEPR Method"
    width=720/>
</div>


Official repository for the  **PEPR: Privileged Event-based Predictive Regularization for Domain Generalization**, accepted at **CVPR26 Findings**.

PEPR tackles domain shift in visual perception by leveraging event data as privileged information during training. Instead of aligning RGB and event features, it trains the RGB model to predict event representations in a shared latent space—capturing robustness without losing semantic detail.
The result is a standard RGB model at inference that generalizes better across domain shifts (e.g., day-to-night), outperforming alignment-based methods.


---

## 📂 Code Structure


Code for semantic segmentation and detection coming soon!

---

## 📥 Datasets

- **FRED**  
  Available on 🤗 Hugging Face:  
  https://huggingface.co/datasets/GabrieleMagrini/FRED  

- **DSEC**  
  Includes annotations for object detection and semantic segmentation:  
  https://dsec.ifi.uzh.ch/  

- **Hard-DSEC-Det**  
  See the official repository:  
  https://github.com/djessy1998/EA-DETR  

- **Cityscapes**  
  Available in the official website:  
  https://www.cityscapes-dataset.com/  

- **Cityscapes Adverse**  
  Available on 🤗 Hugging Face:  
  https://huggingface.co/datasets/naufalso/cityscape-adverse  


To simulate the event version of cityscapes, please refer to the official [VID2E](https://github.com/uzh-rpg/rpg_vid2e) repository.
---


## 🖼️ Results


<div align="center">
  <h1 style="font-size: 2rem; margin-bottom: 1rem; color: #fff;">Segmentation</h1>
  
  <img src="https://github.com/miccunifi/PEPR/blob/main/static/images/segmentation.png?raw=true"/>
</div>

<div align="center">
  <h1 style="font-size: 2rem; margin-bottom: 1rem; color: #fff;">Detection</h1>
  
  <img src="https://github.com/miccunifi/PEPR/blob/main/static/images/segmentation.png?raw=true"/>
  <img src="https://github.com/miccunifi/PEPR/blob/main/static/images/harddsec.png?raw=true"/>
  <img src="https://github.com/miccunifi/PEPR/blob/main/static/images/segmentation.png?raw=true"/>
</div>



---

<!-- ## Star History
<div align="center">
  <a href="https://www.star-history.com/?repos=miccunifi%2Ffred&type=date&legend=top-left">
   <picture>
     <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=miccunifi/fred&type=date&theme=dark&legend=top-left" />
     <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/chart?repos=miccunifi/fred&type=date&legend=top-left" />
     <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=miccunifi/fred&type=date&legend=top-left" />
   </picture>
  </a>
</div> -->

## ✨ Citation

If you use **PEPR** in your research, please cite:

```
@article{magrini2026pepr,
  title={PEPR: Privileged Event-based Predictive Regularization for Domain Generalization},
  author={Magrini, Gabriele and Becattini, Federico and Biondi, Niccol{\`o} and Pala, Pietro},
  journal={arXiv preprint arXiv:2602.04583},
  year={2026}
}
```



