# PetriLens - Mineração de Dados em isolados de Salmonella enterica

A análise completa está em [`mineracao_salmonella.ipynb`](mineracao_salmonella.ipynb).

## Requisitos

- Python 3.10 ou superior
- `base.csv` na mesma pasta do notebook

## Como rodar

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
jupyter notebook mineracao_salmonella.ipynb
```

No Jupyter, use **Run > Run All Cells**.

## Saídas

- `figuras/`: gráficos em PNG
- `tabelas/`: tabelas em CSV

## Fonte dos dados

Material suplementar S1 de PLoS Genetics: https://pmc.ncbi.nlm.nih.gov/articles/PMC9162342/
