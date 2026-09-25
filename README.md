# Projetos acadêmicos

Repositório com 21 notebooks Jupyter desenvolvidos em Python para atividades acadêmicas. Os arquivos estão organizados em ordemcronológica por unidade, de U1 a U4, com prefixos numéricos para facilitar a navegação.

## Ordem dos projetos

| Ordem | Notebook | Tema principal |
| ---: | --- | --- |
| 01 | [U1 — A1](01-u1-a1.ipynb) | Fundamentos de Python e tipos de dados |
| 02 | [U1 — A2](02-u1-a2.ipynb) | Operadores, comparações e condições |
| 03 | [U1 — A3](03-u1-a3.ipynb) | Listas, loops e entrada de dados |
| 04 | [U1 — A3 — cópia](04-u1-a3-copia-1.ipynb) | Versão adicional do exercício de loops |
| 05 | [U1 — A4](05-u1-a4.ipynb) | Listas e funções |
| 06 | [Atividade prática — U1](06-atividade-pratica-u1.ipynb) | Cálculo de média e situação do aluno |
| 07 | [U2 — A1](07-u2-a1.ipynb) | Manipulação de strings |
| 08 | [U2 — A2](08-u2-a2.ipynb) | Conjuntos e NumPy |
| 09 | [U2 — A4](09-u2-a4.ipynb) | Matemática e gráficos |
| 10 | [Projeto — catálogo de livros](10-projeto-catalogo-de-livros.ipynb) | Classes, listas e visualização de dados |
| 11 | [U3 — A1](11-u3-a1.ipynb) | Banco de dados com SQLite |
| 12 | [U3 — A2](12-u3-a2.ipynb) | Series e DataFrames com pandas |
| 13 | [U3 — A3](13-u3-a3.ipynb) | Manipulação de DataFrames |
| 14 | [U3 — A4](14-u3-a4.ipynb) | Análise e visualização de dados |
| 15 | [Atividade prática — A3](15-atividade-pratica-a3.ipynb) | Análise de vendas com SQLite, pandas e gráficos |
| 16 | [Encerramento — U3](16-encerramento-u3.ipynb) | Consultas e análise de vendas |
| 17 | [U4 — A1](17-u4-a1.ipynb) | Geração de HTML com Python |
| 18 | [U4 — A2](18-u4-a2.ipynb) | Interface web com HTML, CSS e JavaScript |
| 19 | [U4 — A3](19-u4-a3.ipynb) | Funções, validações e testes com `assert` |
| 20 | [Atividade prática — U4](20-atividade-pratica-u4.ipynb) | Classificação do conjunto Iris com rede neural |
| 21 | [Encerramento](21-encerramento.ipynb) | Sistema de vendas, descontos e arredondamento |

## Como executar

1. Abra o notebook desejado diretamente no Google Colab ou faça upload do arquivo `.ipynb` para o Colab.
2. Execute as células na ordem, usando **Shift + Enter**.
3. Preencha as entradas solicitadas pelos exercícios que utilizam `input()`.
4. Alguns notebooks acessam dados externos pela internet. O notebook **U3 — A4** consulta um arquivo CSV remoto; o notebook **U3 — A2** utiliza o arquivo `tarifas_energia_eletrica.csv`, que deve estar disponível no ambiente de execução.

## Dependências

A maioria dos notebooks pode ser executada diretamente no Google Colab. Os projetos que usam análise de dados ou machine learning podem utilizar:

- Python 3
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- TensorFlow/Keras
- SQLite, incluído no Python

## Observações

- Os notebooks foram limpos antes da publicação: resultados de execução e metadados pessoais do Colab foram removidos.
- A ordem numérica dos arquivos representa a sequência acadêmica U1 → U2 → U3 → U4.
- Os notebooks são arquivos independentes, mas alguns reutilizam conceitos apresentados nas unidades anteriores.
