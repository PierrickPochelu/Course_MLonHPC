# Course_MLonHPC
Some materials I developed and co-teach with my colleague O.C.

Layers.ipynb is the file to look at.

Here are some notes about the course flow:
* Previous slides: Logistics regression algo, Big-O notation, SLURM/mpi4py/multiprocessing.
* Layers.ipynb: Common layer algorithms and their respective complexity (compute and memory). Discuss about algorithm decomposition when obvious.
* Next slides: "design patterns" of ML/HPC: independent training: (co-localization or distributed), data-parallel with w/o param. server, model-parallel (layer scale, tensor scale), CPU offloading, ...
* Students are doing homework:
  * coding on HPC 3 algos in Layers.ipynb (ex: distributed KNN, Ensemble of Training/Inference auto-regressor forecasters on the HPC, data-parallel CNN training)
  * using 2 high-level API: PyTorch&Tensorflow/Horovod, HuggingFace/DeepSpeed.

  
