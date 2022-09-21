# Colibrie
 [![image](https://img.shields.io/pypi/v/colibrie.svg)](https://pypi.org/project/colibrie/) [![image](https://img.shields.io/pypi/l/colibrie.svg)](https://pypi.org/project/colibrie/)

Colibrie is a blazing fast tool to extract tables from PDFs 

## Why Colibrie?

- **Blazing fast**: Colibrie is faster by multiple order of magnitude than any solution existing in his category
- **Simple**: Colibrie is plug & play, just give it a PDF, it will give you tables from it
- **Visual fidelity** Colibrie can provide 1:1 HTML representation of any tables it'll find
- **Output**: Each table is extracted into a **pandas DataFrame**, which seamlessly integrates into ETL and data analysis workflows. You can also export tables to multiple formats, which include HTML.

## Installation

### using source
```
pip install poetry

git clone https://github.com/abitoun-42/colibrie.git

cd colibrie

poetry install
```
### using pip
```
pip install colibrie
```

## Usage
```
from colibrie.extract_tables import extract_table

tables = extract_table('pdf_path')
```