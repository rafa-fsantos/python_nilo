# 🐍 Introdução à Programação com Python - Algoritmos e lógica de programação para iniciantes  

Repositório estruturado para anotações, implementação de exemplos e resolução autônoma dos exercícios propostos do livro **"Introdução à Programação com Python: Algoritmos e Lógica de Programação para Iniciantes"**, de autoria de **Nilo Ney Coutinho Menezes** (Editora Novatec - 2024).

---

## 🎯 Objetivos Pedagógicos

* **Teoria Ativa:** Documentar conceitos e explicações intercalados com código executável via Jupyter Notebooks.
* **Prática Autônoma (*Active Recall*):** Resolver exercícios em cadernos separados, mantendo o processo de resolução isolado das respostas e listagens teóricas.
* **Validação Contínua:** Utilizar validações rápidas (`assert`) e testes de casos de borda em cada exercício.
* **Transição Prática:** Praticar execução interativa (notebooks) e desenvolvimento de scripts modulares (`.py`) nos tópicos avançados (arquivos, POO, SQLite e Tkinter).

---

## 🗂️ Estrutura do Diretório (`Python_Nilo`)

A organização separa cada capítulo em sua própria pasta, utilizando a estratégia de **dois notebooks por capítulo** (Teoria/Exemplos e Exercícios) e subpastas de scripts quando necessário:

```text
Python_Nilo/
├── .gitignore
├── README.md
├── cap01-motivacao/
│   └── 01_teoria_e_anotacoes.ipynb
├── cap02-preparando-o-ambiente/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
├── cap03-variaveis-e-entrada-de-dados/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
├── cap04-condicoes/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
├── cap05-repeticoes/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
├── cap06-listas-dicionarios-tuplas-conjuntos/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
├── cap07-trabalhando-com-strings/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
├── cap08-funcoes/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
├── cap09-arquivos/
│   ├── 01_teoria_e_exemplos.ipynb
│   ├── 02_exercicios_propostos.ipynb
│   └── scripts/                     # Leitura/escrita e manipulação de caminhos
├── cap10-classes-e-objetos/
│   ├── 01_teoria_e_exemplos.ipynb
│   ├── 02_exercicios_propostos.ipynb
│   └── scripts/                     # Classes modulares e arquivos importáveis
├── cap11-banco-de-dados/
│   ├── 01_teoria_e_exemplos.ipynb
│   ├── 02_exercicios_propostos.ipynb
│   └── scripts/                     # Conexão e scripts SQLite
├── cap12-modulos-e-expressoes-regulares/
│   ├── 01_teoria_e_exemplos.ipynb
│   └── 02_exercicios_propostos.ipynb
└── cap13-interfaces-graficas/
    ├── 01_teoria_e_anotacoes.ipynb
    └── scripts/                     # Janelas e eventos Tkinter (.py)
```

### Convenções de Arquivos

* `01_teoria_e_exemplos.ipynb`: Conceitos, fórmulas em LaTeX e reprodução comentada dos exemplos do livro.
* `02_exercicios_propostos.ipynb`: Enunciados, funções de resolução, asserções (`assert`) e retrospectivas de aprendizagem.
* `scripts/*.py`: Scripts puros recomendados onde o Jupyter apresenta limitações (Tkinter, criação modular de pacotes e manipuladores de banco de dados).

---

## 📊 Acompanhamento de Progresso

| Capítulo | Título / Tema Principal | Formato Principal | Status | Exercícios Concluídos |
| :---: | :--- | :---: | :---: | :---: |
| **01** | Motivação e Primeiros Passos | Notebook | [x] Concluído | - |
| **02** | Preparando o Ambiente e Primeiros Programas | Notebooks | [ ] Em andamento | 0 / 6 |
| **03** | Variáveis e Entrada de Dados | Notebooks | [ ] Não iniciado | 0 / 15 |
| **04** | Condições (`if`, `else`, `elif`) | Notebooks | [ ] Não iniciado | 0 / 10 |
| **05** | Repetições (`while`, `for`) | Notebooks | [ ] Não iniciado | 0 / 27 |
| **06** | Listas, Dicionários, Tuplas e Conjuntos | Notebooks | [ ] Não iniciado | 0 / 20 |
| **07** | Trabalhando com Strings | Notebooks | [ ] Não iniciado | 0 / 10 |
| **08** | Funções | Notebooks | [ ] Não iniciado | 0 / 15 |
| **09** | Arquivos (Entrada e Saída) | Notebooks + Scripts | [ ] Não iniciado | 0 / 12 |
| **10** | Classes e Objetos (POO) | Notebooks + Scripts | [ ] Não iniciado | 0 / 10 |
| **11** | Banco de Dados (SQLite e SQL) | Notebooks + Scripts | [ ] Não iniciado | 0 / 8 |
| **12** | Módulos e Expressões Regulares | Notebooks + Scripts | [ ] Não iniciado | 0 / 6 |
| **13** | Interfaces Gráficas (Tkinter) | Notebook + Scripts | [ ] Não iniciado | 0 / 5 |

---

## ⚙️ Ambiente de Desenvolvimento

### 1. Pré-requisitos

* Python 3.14+ (ou ambiente Conda/Miniconda)
* JupyterLab, Jupyter Notebook ou extensão do Jupyter para VS Code

### 2. Configurando o Ambiente Conda

```bash
# Criação do ambiente com Python e Jupyter
conda create -n python_nilo python=3.14 jupyterlab -y

# Ativação do ambiente
conda activate python_nilo
```

### 3. Como Executar os Cadernos

Pelo terminal, dentro da pasta raiz:

```bash
jupyter lab
```

Navegue pelo painel lateral até a pasta do capítulo desejado (`cap03-...`, `cap04-...`) e abra o notebook `01_teoria_e_exemplos.ipynb` ou `02_exercicios_propostos.ipynb`.

---

## 🔗 Referências Oficiais

* [Site Oficial do Livro (Nilo Ney)](https://python.nilo.pro.br/)
* [Editora Novatec - Página do Livro](https://novatec.com.br/livros/introducao-python-4ed)
* [Documentação Oficial do Python 3](https://docs.python.org/pt-br/3/)

---
*Repositório acadêmico voltado ao aprendizado individual e registro de evolução técnica.*
