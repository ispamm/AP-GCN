# Adaptive Propagation Graph Convolutional Network (AP-GCN)

This is the companion code for the paper:
[Adaptive Propagation Graph Convolutional Network](https://arxiv.org/abs/1905.01907), *arXiv:1905.01907*, 2020.

### The Spectral K

We introduce the adaptive propagation graph convolutional network (AP-GCN), a variation of GCN wherein each node selects automatically the number of propagation steps performed across the graph.

![Schematics of the proposed framework.](https://github.com/spindro/AP-GCN/blob/master/apgcn.png)

### Organization of the code

All the code for the models described in the paper can be found in *model.py*. An example of use which can be quickly extendet to the full experimental evaluation is provided in *AP-GCN_demo.ipynb*.

### References

[1] Kipf, T.N. and Welling, M., 2016. **Semi-supervised classification with graph convolutional networks**. arXiv preprint arXiv:1609.02907.


[2] Klicpera J., Bojchevski A., Günnemann S. **Predict then Propagate: Graph Neural Networks meet Personalized PageRank**. arXiv preprint arXiv:1810.05997


