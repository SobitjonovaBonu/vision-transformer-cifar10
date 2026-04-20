# Vision Transformer — CIFAR-10 Image Classification

## Loyiha haqida
Vision Transformer (ViT) modelini CIFAR-10 dataseti bilan train qilib,
rasm klassifikatsiyasini amalga oshiruvchi loyiha.

## Natijalar
| Epoch | Train Accuracy | Val Accuracy |
|-------|---------------|--------------|
| 1     | 80.21%        | 86.75%       |
| 2     | 88.42%        | 90.74%       |
| 3     | 92.86%        | 92.61%       |
| 4     | 96.47%        | 94.41%       |
| 5     | 98.76%        | 96.05%       |

## Dataset
- **CIFAR-10** — 60,000 rasm, 10 ta class
- Train: 50,000 | Test: 10,000

## Model
- **ViT-B/16** — pretrained on ImageNet
- Fine-tuned on CIFAR-10

## Texnologiyalar
- Python 3.12
- PyTorch 2.5.1 + CUDA
- torchvision
- matplotlib

## Classes
airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

## Ishlatish
```bash
pip install torch torchvision matplotlib
```

Notebook ni ishga tushiring: `lora.ipynb`
