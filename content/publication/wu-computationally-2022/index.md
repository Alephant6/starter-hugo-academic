---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Computationally Efficient Optimal Wigner Distribution in LCT Domains for
  Detecting Noisy LFM Signals
subtitle: ''
summary: ''
authors:
- An-Yang Wu
- Xi-Ya Shi
- Yun Sun
- Xian Jiang
- Sheng-Zhou Qiang
- Pu-Yu Han
- Yun-Jie Chen
- Zhi-Chao Zhang
tags: []
categories: []
date: '2022-02-15'
lastmod: 2022-06-23T17:15:40+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-06-23T09:15:39.350429Z'
publication_types:
- '2'
abstract: Recently, Wigner distribution (WD) associated with linear canonical transforms
  (LCTs) is quickly becoming a promising technique for detecting linear frequency-modulated
  (LFM) signals corrupted with noises by establishing output signal-to-noise ratio
  (SNR) inequality model or optimization model. Particularly, the closed-form instantaneous
  cross-correlation function type of WD (CICFWD), a unified linear canonical Wigner
  distribution, has shown to be competitive in detecting noisy LFM signals under an
  extremely low SNR. However, the CICFWD has up to nine LCT free parameters so that
  it requires a heavy computational load. To improve the efficiency of real-time processing,
  this paper focuses on the instantaneous cross-correlation function type of WD (ICFWD),
  which has only six LCT free parameters but is not a special case of the CICFWD.
  The main advantage of ICFWD is that it could be expected to reduce the computational
  complexity while maintaining detection performance. This paper first proposes an
  optimization model to the ICFWD’s output SNR with respect to deterministic signals
  embedded in additive zero-mean noises. It then deduces the model’s solution to a
  single component LFM signal added with white noise, leading to the optimal selection
  strategy on LCT free parameters. Simulation results demonstrate that the ICFWD improves
  almost a doubling of computing speed in comparison with the CICFWD while sharing
  the same level of detection performance. To be specific, the computing time of ICFWD
  in sampling frequencies 5 Hz, 10 Hz, 15 Hz, and 20 Hz is about 0.048 s, 0.111 s,
  0.226 s, and 0.392 s, respectively, while 0.075 s, 0.233 s, 0.478 s, and 0.821 s
  for the computing time of CICFWD; the ICFWD and CICFWD have nearly the same output
  SNR higher than that of the WD.
publication: ''
doi: 10.1155/2022/2036285
links:
- name: URL
  url: https://www.hindawi.com/journals/mpe/2022/2036285/
---
