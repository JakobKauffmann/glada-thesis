# Targeted Bottlenecking of Self-Supervised Speech Layers for Generalizable Audio Deepfake Detection

Master's thesis (Master's Project) by **Jakob Kauffmann**, Department of Computer Science, San José State University, Spring 2026.

**Status:** Defended May 2026. The full text and code are under embargo until May 2027. This repository holds the abstract and citations only.

**DOI:** [10.31979/etd.kmc6-t6vf](https://doi.org/10.31979/etd.kmc6-t6vf) · [ScholarWorks record](https://scholarworks.sjsu.edu/etd_projects/1804) (full text available for download on May 26, 2027)

**Advisor:** Dr. Faranak Abri · **Committee:** Dr. Amith Kamath Belman, Dr. Saptarshi Sengupta

## Abstract

From the [ScholarWorks record](https://scholarworks.sjsu.edu/etd_projects/1804):

> Audio deepfake detectors trained on one corpus often generalize poorly to unfamiliar recording channels, codecs, and synthesizers. This project examines where in a self-supervised speech model the channel and codec nuisance is concentrated, and introduces GLADA, an architecture that aggregates SSL hidden states by layer group, applies a Variational Information Bottleneck and an adversarial domain discriminator to each group, and encourages group diversity through a CKA penalty. A multi-seed cross-dataset study on In-the-Wild, ASVspoof 2021 LA, ASVspoof 2021 DF, WaveFake, and CodecFake+ finds that restricting the bottleneck to the lowest layer group outperforms both a single post-pooling bottleneck and the full per-group placement on every secondary out-of-domain dataset. Per-group linear probes and per-group CKA against handcrafted acoustic descriptors both localize codec and channel signal to that lowest group, which supports the placement.

**Keywords:** audio deepfake detection, self-supervised speech models, variational information bottleneck, per-layer-group bottleneck, adversarial domain adaptation, cross-domain generalization

## Publications from this research

- J. Kauffmann, F. Abri, and J. Webb, "Per-Layer-Group Bottlenecking for Cross-Domain Audio Deepfake Detection," IEEE International Conference on Tools with Artificial Intelligence (ICTAI 2026), accepted.
- J. Kauffmann, F. Abri, and J. Webb, "Speech Deepfake Detection: A Survey of Methods, Benchmarks, and Generalization Challenges," in *Artificial Intelligence for Cyber Defense in Emerging Threats*, M. Stamp, Ed. Springer, forthcoming 2027.
- J. Kauffmann, F. Abri, and J. Webb, "Audio Deepfake Detection: Cross-Domain Generalization and Grouped Layer Adversarial Domain Adaptation," IEEE COMPSAC 2026, accepted, withdrawn. An earlier paper on grouped layer adversarial domain adaptation (GLADA), written before the per-layer-group bottleneck work.

Links to the ICTAI paper and the chapter will be added once they are published.

## Citation

```bibtex
@mastersthesis{kauffmann2026targeted,
  author = {Kauffmann, Jakob},
  title  = {Targeted Bottlenecking of Self-Supervised Speech Layers for Generalizable Audio Deepfake Detection},
  school = {San Jos{\'e} State University},
  type   = {Master's Project},
  number = {1804},
  year   = {2026},
  doi    = {10.31979/etd.kmc6-t6vf},
  url    = {https://scholarworks.sjsu.edu/etd_projects/1804}
}

@inproceedings{kauffmann2026perlayergroup,
  author    = {Kauffmann, Jakob and Abri, Faranak and Webb, Jade},
  title     = {Per-Layer-Group Bottlenecking for Cross-Domain Audio Deepfake Detection},
  booktitle = {IEEE International Conference on Tools with Artificial Intelligence (ICTAI)},
  year      = {2026},
  note      = {Accepted}
}

@incollection{kauffmann2027survey,
  author    = {Kauffmann, Jakob and Abri, Faranak and Webb, Jade},
  title     = {Speech Deepfake Detection: A Survey of Methods, Benchmarks, and Generalization Challenges},
  booktitle = {Artificial Intelligence for Cyber Defense in Emerging Threats},
  editor    = {Stamp, Mark},
  publisher = {Springer},
  year      = {2027},
  note      = {Forthcoming}
}
```

## Contact

Jakob Kauffmann · [jakobkauffmann.github.io](https://jakobkauffmann.github.io) · [Google Scholar](https://scholar.google.com/citations?user=LZN0dxQAAAAJ) · [LinkedIn](https://linkedin.com/in/jakobkauffmann)
