# Compactação de arquivos

Arquivos pesados costumam apresentar lentidão no Power Bi, então para melhorar o desempenho foi compacatado os arquivos através desse código.

## TECNOLOGIAS USADAS:
- Python 3.11.5
- Jupyter Notebook 5.3.0
  - polars == 0.20.10
  - os == 3.11.5

## Instalação da biblioteca
```bash
pip install polars
```

## DESENVOLVIMENTO
- Biblioteca os para percorrer as pastas e subpastas que contenham arquivos no formato csv;
- Com o polars será feito a leitura dos arquivos encontrados, utilizando parâmetros específicos para que seja feita a leitura correta;
- Converter os arquivos csv para parquet, nesse momento é feito a compactação;
- Salvá-los em um outro diretório.
