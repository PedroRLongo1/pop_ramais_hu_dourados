# Gerenciador de ramais

Automação para gerenciamento de ramais hospitalares. Feito com python com interface gráfica no PySide6

## 🧠 Objetivo

Automatizar o processo de gerir os ramais e gerar a lista de consulta desses ramais para o H.U. dourados

## ⚙️ Tecnologias utilizadas

- Python 3
- PySide6 (interface gráfica)
- Pandas, OpenPyXL (manipulação de planilhas Excel)
- PyInstaller (geração do executável)

## 📁 Estrutura do projeto
```
📁 src/
├── 📁 models/
│  ├── 📝 actions.py                 # Funções que interagem com o banco de dados
│  ├── 📝 conversor.py               # Funções que atuam na conversão dos ramais
│  ├── 📝 show_options.py            # Funções que modificam a tela exibida
├── 📝 imports.py                    # Importações feitas no arquivo
├── 📝 main_pyside6.py               # Arquivo principal (inicialização da Ui)
├── 📝 Ramais.xlsx                   # Arquivo de banco de dados
├── 📝 style.qss                     # Estilização da parte gráfica
├── 📝 Ui.py                         # Interface gráfica
📝 .gitignore                    # Arquivos e pastas ignorados pelo Git
📝 README.md                     # Documentação principal do projeto
```

## 🛠️ Instalação para desenvolvedores

Clone o repositório e instale as dependências com:

Clone do repositório:
```bash
git clone https:/PedroRLongo1/gerenciador-de-ramais-hu-dourados.git
```

## 🖥️ Como usar

O projeto é distribuído como um arquivo `.exe`.  
Para versões de desenvolvimento:

```bash
python3 src/main_pyside6.py
```

## 📦 Dependências

Foram utilizadas as seguintes bibliotecas:

* Pyside6
* pandas

## 🚫 Contribuição

Este projeto é **privado**, de uso exclusivo do Hospital Universitário da Universidade Federal da Grande Dourados – HU-UFGD. Não são aceitas contribuições externas.

## 🔐 Licença

Este software é de uso interno e exclusivo  do Hospital Universitário da Universidade Federal da Grande Dourados – HU-UFG.
É **proibida** sua distribuição ou modificação sem autorização prévia.
