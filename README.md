# ROCm PyTorch Playground

Sandbox for PyTorch + AMD ROCm experiments.

## Goals
- Confirm ROCm-enabled PyTorch installs
- Smoke-test GPU tensor ops
- Note common setup pitfalls

## Checklist
- Install ROCm drivers
- Install PyTorch with ROCm
- Verify torch.cuda.is_available()
- Start with tiny tensors

## Hello world

```python
import torch
print(torch.__version__, torch.cuda.is_available())
if torch.cuda.is_available():
    x = torch.randn(256, 256, device="cuda")periments.
    print((x @ x).shape)
```

Independent learning ex


















