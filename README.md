# MoE-E2E — Pilot-Free End-to-End Communication

Official implementation for  
**“A Pilot-Free End-to-End Communication System Using Complex Convolutional Encoder and Mixture-of-Experts Based Decoder.”**  
Yulai Han, Jingbo Tan, Rui Zeng, Jintao Wang (BNRist, Tsinghua University). *(WCNC 2026 submission)*

## Quick Start
```bash
# env
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt

# train / eval (示例命令，按你项目改)
python scripts/train.py --config configs/base.yaml
python scripts/eval.py  --config configs/base.yaml
