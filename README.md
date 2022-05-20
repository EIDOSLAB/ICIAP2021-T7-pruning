# EIDOSLab ICIAP Tutorial

## Making deep neural networks efficient with PyTorch

State-of-the-art deep learning techniques rely on over-parametrized models that are hard to deploy. On the contrary,
biological neural networks are known to use efficient sparse connectivity. Identifying optimal techniques to compress
models by reducing the number of parameters in them is important in order to reduce memory, battery, and hardware
consumption without sacrificing accuracy, deploy lightweight models on device, and guarantee privacy with private
on-device computation.

In this notebook we will leverage on the PyTorch’s `nn.utils.prune` package to show the difference between unstructured
and structured sparsification in a one-shot pruning procedure.
We will:

1. Cover the basics of torch.nn.utils.prune.
2. Apply unstructured and structured pruning procedures (with and without fine-tuning).
3. Introduce simplify to exploit the introduced structured sparsity.

To use the notebook, simply upload it to a Jupyter instance and follow along the notebook's cells.
The notebook can be downloaded from the Drive folder https://drive.google.com/drive/folders/1IonOF6lo_7Son1cSqkdZrYlO8o2MVaAe?usp=sharing
