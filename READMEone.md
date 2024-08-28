# Extração de Título de PDF

Este repositório contém um script Python para extrair o texto de um arquivo PDF e identificar um título a partir das primeiras linhas do texto extraído. O script utiliza a biblioteca `PyMuPDF` para a extração de texto e expressões regulares para localizar o título.

## Funcionalidade

O script realiza as seguintes operações:

1. **Extrair Texto de um PDF**: Abre um arquivo PDF e extrai o texto de cada página.
2. **Encontrar Título**: Captura as primeiras três linhas do texto extraído para identificar o título.

## Código

O script Python inclui as seguintes funções:

```python
import fitz  # PyMuPDF (pip install PyMuPDF)
import re

```
# Considerações

O padrão de expressão regular utilizado no script captura exatamente três linhas do início do texto extraído. Você pode ajustar o padrão conforme necessário para diferentes formatos de títulos.  
