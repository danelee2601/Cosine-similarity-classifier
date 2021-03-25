# Cosine-similarity-classifier

*Cosine similarity classifier* introduced in [S. Gidaris et al., 2018](https://openaccess.thecvf.com/content_cvpr_2018/papers/Gidaris_Dynamic_Few-Shot_Visual_CVPR_2018_paper.pdf) is implemented in PyTorch, and it is compared to the linear classifier.<br>

# Findings
- the use of the temperature parameter τ substaionally improves the quality of the learned representations.
- In the test setting, the class `7` is treated as a novel class. Without the temperature, the prototype evaluation resulted in the accuracy of 52%, but with the temperature, the accuracy increased to 84%.
- With the `weight decay` as 1e-6 as in SimCLR and BYOL, the accuracy increases to 86%. 
