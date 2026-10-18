# EN3160 Assignment 3

Jupyter notebook for CIFAR-10 manual backpropagation, MNIST CNN comparisons, and ResNet18 transfer learning on ants and bees. The experiments were run on CPU.

- [Notebook with results](assignment_03.ipynb)
- [HTML preview](assignment_03.html)
- [Assignment brief](en3160_assignment_03.pdf)
- [Metrics and figures](results/)

Install the CPU build of PyTorch and torchvision, then the notebook dependencies:

```bash
python -m pip install torch torchvision --index-url https://download.pytorch.org/whl/cpu
python -m pip install -r requirements.txt
```

Open `assignment_03.ipynb` in Jupyter or VS Code and select the Python environment containing those packages. The notebook downloads CIFAR-10, MNIST, the hymenoptera dataset, and pretrained ResNet18 weights when needed. Downloaded data and model checkpoints are kept locally and excluded from Git.
