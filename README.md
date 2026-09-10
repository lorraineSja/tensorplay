# tensorplay

Tiny CNN experiments on synthetic image data

Small but I use it weekly.

## How to use

```bash
python train.py --epochs 5 --synthetic
# metrics land in runs/metrics.csv
```

## Features

- Single file model definition, easy to hack
- Cosine LR schedule with warmup
- Metrics logged to CSV for plotting
- Gradient clipping and clean metrics logging
- Synthetic dataset mode: no download needed to smoke-test

## Installation

```bash
pip install -r requirements.txt
```

## Project structure

```text
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── model.py
├── requirements.txt
└── train.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT licensed, see LICENSE.
