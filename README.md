# Abrir Portfólio no Google Drive com Python

Este projeto contém um código simples em Python que abre automaticamente o seu portfólio hospedado no Google Drive em um navegador.

## Passo 1: Criar o Código

1. Abra um editor de código, como o **VSCode** ou **PyCharm**, e crie um arquivo Python com o nome `abrir_portfolio.py`.

2. Adicione o seguinte código no arquivo:

```python
import webbrowser


link_portfolio = "https://drive.google.com/your-portfolio-link-here"

webbrowser.open(link_portfolio)
