<div align="center">
<a href="http://camma.u-strasbg.fr/">
<img src="static/camma_logo_tr.png" width="30%">
</a>
</div>


## **Jumpstarting Surgical Computer Vision**

_Deepak Alapatt, Aditya Murali, [Vinkle Srivastav](https://vinkle.github.io/), Pietro Mascagni, AI4SafeChole Consortium, Nicolas Padoy_, **MICCAI, 2024**

[![arXiv](https://img.shields.io/badge/arxiv-2207.00449-red)](https://arxiv.org/abs/2312.05968)


## Code coming soon

### Introduction
<div style="text-align: left">
Consensus amongst researchers and industry points to a lack of large, representative annotated datasets as the biggest obstacle to progress in the field of surgical data science. Advances in Self-Supervised Learning (SSL) represent a solution, reducing the dependence on large labeled datasets by providing task-agnostic initializations. However, the robustness of current self-supervised learning methods to domain shifts remains unclear, limiting our understanding of its utility for leveraging diverse sources of surgical data. Shifting the focus from methods to data, we demonstrate that the downstream value of SSL-based initializations is intricately intertwined with the composition of pre-training datasets. These results underscore an important gap that needs to be filled as we scale self-supervised approaches toward building general-purpose ``foundation models'' that enable diverse use-cases within the surgical domain. Through several stages of controlled experimentation, we develop recommendations for pretraining dataset composition evidenced through over 300 experiments spanning 20 pre-training datasets, 9 surgical procedures, 7 centers (hospitals), 3 labeled-data settings, 3 downstream tasks, and multiple runs. Using the approaches here described, we outperform state-of-the-art pre-trainings on two public benchmarks for phase recognition: up to 2.2% on Cholec80 and 5.1% on AutoLaparo. 
</div>


## Citation

```bibtex
@article{alapatt2023jumpstarting,
  title={Jumpstarting Surgical Computer Vision},
  author={Alapatt, Deepak and Murali, Aditya and Srivastav, Vinkle and Mascagni, Pietro and Consortium, AI4SafeChole and Padoy, Nicolas},
  booktitle={International conference on medical image computing and computer-assisted intervention},
  year={2024},
  organization={Springer}
}
```

```bibtex
@article{ramesh2023dissecting,
  title={Dissecting self-supervised learning methods for surgical computer vision},
  author={Ramesh, Sanat and Srivastav, Vinkle and Alapatt, Deepak and Yu, Tong and Murali, Aditya and Sestini, Luca and Nwoye, Chinedu Innocent and Hamoud, Idris and Sharma, Saurav and Fleurentin, Antoine and others},
  journal={Medical Image Analysis},
  pages={102844},
  year={2023},
  publisher={Elsevier}
}
```

### References
The project uses [VISSL](https://github.com/facebookresearch/vissl). We thank the authors of VISSL for releasing the library. If you use VISSL, consider citing it using the following BibTeX entry.
```bibtex
@misc{goyal2021vissl,
  author =       {Priya Goyal and Quentin Duval and Jeremy Reizenstein and Matthew Leavitt and Min Xu and
                  Benjamin Lefaudeux and Mannat Singh and Vinicius Reis and Mathilde Caron and Piotr Bojanowski and
                  Armand Joulin and Ishan Misra},
  title =        {VISSL},
  howpublished = {\url{https://github.com/facebookresearch/vissl}},
  year =         {2021}
}
```

## License
This code, models, and datasets are available for non-commercial scientific research purposes as defined in the [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). By downloading and using this code you agree to the terms in the [LICENSE](LICENSE). Third-party codes are subject to their respective licenses.
