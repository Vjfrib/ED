<p><a target="_blank" href="https://app.eraser.io/workspace/fnPMTha9Hwwjz8WsEtCm" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange?logo=jupyter)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](LICENSE)

<!--- Eraser file: https://app.eraser.io/workspace/fnPMTha9Hwwjz8WsEtCm --->

Repositório acadêmico da disciplina **Estrutura de Dados**, desenvolvido por **Vinícius Ribeiro** durante o semestre **2024.1**, com listas, experimentos e projetos em Python sobre estruturas lineares, recursão, ordenação, árvores, grafos e grafos de conhecimento.

O objetivo deste repositório é reunir implementações e estudos práticos de estruturas de dados, com foco em compreensão conceitual, experimentação em notebooks e aplicação dos temas em problemas computacionais.

> **Professor:** Prof. Dr. Cleyton Mário  
> **Disciplina:** Estrutura de Dados  
> **Discente:** Vinícius Ribeiro

---

## 📌 Visão geral

Este repositório contém diferentes atividades da disciplina, organizadas principalmente em notebooks Jupyter/Google Colab. Os materiais incluem:

- listas resolvidas de Estrutura de Dados;
- códigos em Python para TDAs e algoritmos clássicos;
- experimentos com análise de complexidade;
- implementações de listas, pilhas, filas, deques, árvores e grafos;
- projeto/seminário sobre algoritmos em grafos;
- projeto final envolvendo ontologias, grafos de conhecimento e processamento de texto.

---

## 🧠 Conteúdos abordados

| Tema | Conteúdo trabalhado |
|---|---|
| Tipos abstratos de dados | Fila de prioridade, pilha, fila, deque e fila circular |
| Recursão | Série de Collatz, Torres de Hanoi e pilha de chamadas |
| Listas encadeadas | Lista circular ordenada, mesclagem de listas e operações em nós |
| Pilhas e filas | Implementações com `collections.deque` e lista encadeada |
| Deques | Inserção e remoção nas duas extremidades |
| Ordenação | QuickSort, mediana de três, counting sort e comparação de desempenho |
| Complexidade | Medição de tempo, análise de listas aleatórias e listas descendentes |
| Árvores | Árvore binária, inserção, exclusão, repetição de nós e rotações AVL |
| Grafos | Algoritmo de Hierholzer e grafos eulerianos |
| Grafos de conhecimento | Ontologias, RDF/OWL, NetworkX, Owlready2, spaCy e Transformers |

---

## 📂 Estrutura do repositório

```text
ED---Data-Structures-main/
├── README.md
├── LICENSE
├── Lista_4_ED.ipynb
├── Projeto_Final_ED.ipynb
├── listas/
│   ├── Lista 1/
│   │   └── lista_1_ed.ipynb
│   ├── Lista 2/
│   │   └── Lista_2_ED_Old.ipynb
│   ├── Lista 3/
│   │   ├── Lista_3_ED.ipynb
│   │   └── Lista_3_ED_Old.ipynb
│   ├── Lista 4/
│   │   └── Lista_4_ED.ipynb
│   └── readme.txt
├── Projeto/
│   ├── Projeto_Final_ED.ipynb
│   ├── Proj. final - Grafos de conhecimento/
│   │   └── Ontology,_Knowledge_Graph,_LLM_&_Corpus_textual.ipynb
│   └── Seminário sobre Grafos/
│       └── Seminário,_Estrutura_de_dados.ipynb
└── scripts/
    └── Primeira Tentativa.ipynb
```

---

## 📘 Listas e atividades

### Lista 1 — Recursão, filas e listas circulares

A primeira lista trabalha fundamentos de tipos abstratos de dados, recursão e listas encadeadas.

Principais tópicos:

- conceito de **fila de prioridade** como TDA;
- comparação entre abordagens recursivas e iterativas;
- Série de Collatz;
- Torres de Hanoi;
- pilha de chamadas em recursão;
- inserção ordenada em **lista encadeada circular**;
- mesclagem de listas encadeadas ordenadas.

Arquivo principal:

```text
listas/Lista 1/Submissão L1/ED Lista 1/Lista_1_ed.ipynb
```

---

### Lista 2 — Deque, fila circular e pilhas

A segunda lista aprofunda estruturas lineares e implementações alternativas.

Principais implementações:

- `Deck` / `Deque`;
- `DeckBuffado`;
- remoção de duplicatas;
- fila circular;
- inversão de pilha;
- pilha com `collections.deque`;
- pilha com lista encadeada;
- classes `Node` e `PilhaListaEncadeada`.

Arquivo principal:

```text
listas/Lista 2/Submissão/ED Lista 2/Lista_2_ED.ipynb
```

---

### Lista 3 — Complexidade e algoritmos de ordenação

A terceira lista trabalha comparação de algoritmos, medição de tempo e discussão de complexidade.

Principais tópicos:

- QuickSort;
- QuickSort com **mediana de três**;
- counting sort;
- comparação de tempo entre algoritmos de ordenação;
- testes com listas aleatórias de diferentes tamanhos;
- testes com lista descendente;
- busca de par com soma específica;
- análise de complexidade.

Arquivo principal:

```text
listas/Lista 3/Lista_3_ED.ipynb
```

---

### Lista 4 — Árvores binárias e AVL

A quarta lista trabalha conceitos de árvores e operações fundamentais.

Principais tópicos:

- uso de árvores na Teoria da Computação;
- aplicação de árvores em compiladores e interpretadores;
- árvore binária;
- verificação se uma estrutura é árvore binária;
- inserção e exclusão em árvore binária;
- tratamento de valores repetidos;
- rotações em árvores AVL.

Arquivo principal:

```text
Lista_4_ED.ipynb
```

---

## 🔎 Projeto/seminário sobre grafos

O repositório também inclui um seminário sobre **algoritmos em grafos**, com foco no **Algoritmo de Hierholzer**, utilizado para encontrar circuitos/caminhos eulerianos.

Principais tópicos:

- grafos eulerianos;
- funcionamento do algoritmo de Hierholzer;
- vantagens e limitações;
- implementação em Python;
- visualização com `networkx` e `matplotlib`.

Arquivo:

```text
Projeto/Seminário sobre Grafos/Seminário,_Estrutura_de_dados.ipynb
```

---

## 🧬 Projeto final — Ontologias, grafos de conhecimento, LLM e corpus textual

O projeto final explora a relação entre Estrutura de Dados, grafos e representação semântica de conhecimento.

Principais recursos utilizados:

- `owlready2` para criação de ontologias;
- `networkx` para modelagem e visualização de grafos;
- `matplotlib` e `pydot` para visualização;
- `spaCy` para processamento de linguagem natural;
- `transformers` e `torch` para uso de modelos de linguagem;
- `pdfplumber` para extração de texto de PDFs.

Arquivos principais:

```text
Projeto_Final_ED.ipynb
Projeto/Proj. final - Grafos de conhecimento/Ontology,_Knowledge_Graph,_LLM_&_Corpus_textual.ipynb
```

---

## 🚀 Como executar

### Opção 1 — Abrir no Google Colab

Os notebooks podem ser abertos no Google Colab. Essa é a forma mais simples para executar as listas sem configurar ambiente local.

1. Abra o notebook desejado no GitHub.
2. Clique no botão **Open in Colab**, quando disponível.
3. Execute as células em ordem.

---

### Opção 2 — Executar localmente

Clone o repositório:

```bash
git clone https://github.com/Vjfrib/ED.git
cd ED
```

Crie e ative um ambiente virtual:

```bash
python -m venv .venv
```

No Windows:

```bash
.venv\Scripts\activate
```

No Linux/macOS:

```bash
source .venv/bin/activate
```

Instale as dependências básicas:

```bash
pip install notebook jupyter numpy matplotlib networkx
```

Para os notebooks de grafos de conhecimento e NLP, instale também:

```bash
pip install owlready2 spacy pdfplumber pydot torch transformers
```

Depois, abra o Jupyter:

```bash
jupyter notebook
```

---

## 🧪 Exemplos de uso

### Executando o algoritmo de Hierholzer

O notebook do seminário implementa uma função para encontrar percurso euleriano em grafos. O fluxo geral é:

```python
grafo = {
    "A": ["B", "D"],
    "B": ["A", "C"],
    "C": ["B", "D"],
    "D": ["A", "C"]
}

caminho = hierholzer(grafo, "A")
print(caminho)
```

### Operações em estruturas lineares

As listas incluem implementações de estruturas como deque, fila circular e pilha:

```python
pilha.push(10)
pilha.push(20)
pilha.pop()
```

### Conversão de dados para grafos

Nos notebooks de grafos de conhecimento, entidades e relações são representadas como classes, propriedades e conexões, aproximando conceitos de Estrutura de Dados de aplicações em IA simbólica e processamento de linguagem natural.

---

## 📊 Destaques técnicos

Este repositório demonstra:

- implementação manual de estruturas de dados em Python;
- uso de notebooks como ambiente de experimentação;
- análise e comparação de algoritmos;
- modelagem de problemas usando grafos;
- conexão entre estruturas de dados clássicas e aplicações modernas em IA;
- uso de bibliotecas Python para visualização, NLP e grafos de conhecimento.

---

## 📚 Documentação e materiais externos

Materiais complementares usados na disciplina:

- [Pasta de listas no Google Drive](https://drive.google.com/drive/folders/1veOaHTRwsxCiu-4L_X2JjXPTQMm3OwTb?usp=sharing)
- [Workspace no Eraser](https://app.eraser.io/workspace/fnPMTha9Hwwjz8WsEtCm)
- [Repositório/espelho no GitLab](https://gitlab.com/ippiki/estrutura-de-dados)

---

## 🧹 Observações de organização

Este repositório possui materiais de estudo, submissões e rascunhos. Alguns arquivos podem representar versões antigas ou alternativas das listas.

Para uma versão mais limpa de portfólio, recomenda-se destacar principalmente:

- `listas/Lista 1/Submissão L1/ED Lista 1/Lista_1_ed.ipynb`
- `listas/Lista 2/Submissão/ED Lista 2/Lista_2_ED.ipynb`
- `listas/Lista 3/Lista_3_ED.ipynb`
- `Lista_4_ED.ipynb`
- `Projeto/Seminário sobre Grafos/Seminário,_Estrutura_de_dados.ipynb`
- `Projeto_Final_ED.ipynb`

---

## 👤 Autor

**Vinícius Ribeiro**  
Estudante de Engenharia da Computação — UPE/POLI

- GitHub: [@Vjfrib](https://github.com/Vjfrib)
- LinkedIn: [/in/vjfrib](https://www.linkedin.com/in/vjfrib/)

---

## 📄 Licença

Este projeto está licenciado sob a licença **Apache License 2.0**. Consulte o arquivo [`LICENSE`](LICENSE) para mais detalhes.
