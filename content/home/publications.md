+++
# Recent Publications widget.
# This widget displays recent publications from `content/publication/`.
widget = "publications"
active = true
date = 2016-04-20T00:00:00

title = "Publications"
subtitle = ""

# Order that this section will appear in.
weight = 20

# Number of publications to list.
count = 10

# List format.
#   0 = Simple
#   1 = Detailed
#   2 = APA
#   3 = MLA
#   4 = Stream
list_format = 4

# Filter by publication type.
# -1: Any
#  0: Uncategorized
#  1: Conference proceedings
#  2: Journal
#  3: Work in progress
#  4: Technical report
#  5: Book
#  6: Book chapter
publication_type = "-1"

# Exclude publications that are shown in the Selected Publications widget?
exclude_selected = false

# Lip Movements Generation at a Glance



### Abstract

Cross-modality generation is an emerging topic that aims to synthesize data in one modality based on information in a different modality. In this paper, we consider a task of such: given an arbitrary audio speech and one lip image of arbitrary target identity, generate synthesized lip movements of the target identity saying the speech. To perform well in this task, it inevitably requires a model to not only consider the retention of target identity, photo-realistic of synthesized images, consistency and smoothness of lip images in a sequence, but more importantly, learn the correlations between audio speech and lip movements. To solve the collective problems, we explore the best modeling of the audio-visual correlations in building and training a lip-movement generator network. Specifically, we devise a method to fuse audio and image embeddings to generate multiple lip images at once and propose a novel correlation loss to synchronize lip changes and speech changes. Our final model utilizes a combination of four losses for a comprehensive consideration in generating lip movements; it is trained in an end-to-end fashion and is robust to lip shapes, view angles and different facial characteristics. Thoughtful experiments on three datasets ranging from lab-recorded to lips in the wild show that our model significantly outperforms other state-of-the-art methods extended to this task.

[pdf](http://openaccess.thecvf.com/content_ECCV_2018/papers/Lele_Chen_Lip_Movements_Generation_ECCV_2018_paper.pdf), bibtex

```
@InProceedings{Chen_2018_ECCV,
author = {Chen, Lele and Li, Zhiheng and K Maddox, Ross and Duan, Zhiyao and Xu, Chenliang},
title = {Lip Movements Generation at a Glance},
booktitle = {The European Conference on Computer Vision (ECCV)},
month = {September},
year = {2018}
}
```