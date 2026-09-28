# LIBERO ACT Training Artifacts

- Policy: ACT
- Dataset: `lerobot/libero`
- Task suite: `libero_spatial`
- Steps: 100,000
- Train loss: 0.199
- Eval success rate: 1.0% (1/100)
- Eval date: 2026-09-27

## Model weights

The 198MB `model.safetensors` is hosted on HuggingFace Hub:
https://huggingface.co/Mxue123/act-libero-spatial

## Contents

- `config.json` / `train_config.json`: training config
- `policy_*.json` / `policy_*_processor.safetensors`: normalization processors
- `train.log` / `eval.log`: full logs
- `videos/`: 100 evaluation episodes (10 tasks × 10 episodes)
