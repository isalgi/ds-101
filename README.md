# DS-101: Data Science for Supply Chain Management

Kumpulan notebook praktikum mata kuliah Data Science dengan fokus pada rantai pasok beras di Indonesia.

## Pertemuan

| # | Topik | Notebook |
|---|-------|----------|
| 10 | Supply Chain Vulnerability, Risk, Robustness and Resilience | [pertemuan-10.ipynb](pertemuan-10.ipynb) |
| 11 | Sustainable Logistics | [pertemuan-11.ipynb](pertemuan-11.ipynb) |
| 12 | Reverse Logistics + AI Vision | [pertemuan-12.ipynb](pertemuan-12.ipynb) |
| 13 | Information Flows and Technology (Supply Chain Copilot) | [pertemuan-13.ipynb](pertemuan-13.ipynb) |
| 14 | Transportation in Supply Chains (Route Optimization) | [pertemuan-14.ipynb](pertemuan-14.ipynb) |
| 15 | Global Supply Chain (Studi Kasus: Suez Canal Blockage 2021) | [pertemuan-15.ipynb](pertemuan-15.ipynb) |

## Prerequisites

- Python 3.14+
- Jupyter (via VS Code extension)

Install dependencies:

```bash
py -m pip install notebook pandas groq python-dotenv transformers torch pillow ortools
```

## Setup API Key

1. Buat file `.env` di root folder
2. Isi dengan Groq API key:

```
GROQ_API_KEY=your_api_key_here
```

Dapatkan API key gratis di [console.groq.com](https://console.groq.com).

## Struktur Folder

```
ds-101/
├── pertemuan-10.ipynb
├── pertemuan-11.ipynb
├── pertemuan-12.ipynb
├── pertemuan-13.ipynb
├── pertemuan-14.ipynb
├── pertemuan-15.ipynb
├── .env          # tidak di-commit (lihat .gitignore)
└── .gitignore
```
