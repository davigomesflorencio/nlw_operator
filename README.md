# Fundamentos de Visão Computacional com LeNet-5

Este projeto foi desenvolvido durante o **NLW Operator (Trilha Python)** da Rocketseat. O objetivo principal é explorar os fundamentos da visão computacional e do aprendizado profundo através da implementação e treinamento da arquitetura clássica **LeNet-5** utilizando a biblioteca **PyTorch**.

## 🚀 Sobre o Projeto

O projeto consiste na classificação de dígitos manuscritos utilizando o famoso dataset **MNIST**. Através deste desafio, aplicamos conceitos essenciais de Redes Neurais Convolucionais (CNNs), incluindo:

- Pré-processamento e carregamento de dados com `torchvision`.
- Implementação detalhada da arquitetura LeNet-5 (Yann LeCun et al.).
- Ciclo de treinamento e validação de modelos de Deep Learning.
- Visualização de Mapas de Características (Feature Maps).
- Análise de erros e métricas de desempenho.

## 🛠 Tecnologias Utilizadas

- **Python**: Linguagem base para o desenvolvimento.
- **PyTorch**: Framework de Deep Learning para construção e treinamento do modelo.
- **Torchvision**: Utilizado para manipulação de datasets e transformações de imagem.
- **Matplotlib**: Para visualização de dados e resultados.
- **NumPy**: Para operações matemáticas e manipulação de arrays.
- **Jupyter Notebook**: Ambiente para experimentação e documentação.

## 🏗 Arquitetura LeNet-5

O modelo segue a estrutura clássica proposta em 1998, composta por:
1. **Camada Convolucional 1**: 6 filtros 5x5 + Ativação Tanh/ReLU.
2. **Subsampling (Average Pooling)**: Redução de dimensionalidade 2x2.
3. **Camada Convolucional 2**: 16 filtros 5x5 + Ativação Tanh/ReLU.
4. **Subsampling (Average Pooling)**: Redução de dimensionalidade 2x2.
5. **Camada Totalmente Conectada (FC1)**: 120 neurônios.
6. **Camada Totalmente Conectada (FC2)**: 84 neurônios.
7. **Camada de Saída**: 10 neurônios (um para cada dígito).

## 📁 Estrutura do Repositório

```text
├── data/               # Diretório para o dataset MNIST
├── notebooks/          # Notebooks de estudo e implementação
│   └── lenet5_mnist.ipynb
├── models/             # Pesos do modelo treinado (se aplicável)
├── requirements.txt    # Dependências do projeto
└── README.md           # Documentação do projeto
```

## 🔧 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/nlw-operator-python-lenet5.git
   cd nlw-operator-python-lenet5
   ```

2. **Crie um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Execute o notebook:**
   Abra o arquivo `notebooks/lenet5_mnist.ipynb` no seu editor ou via `jupyter notebook`.

## 🎓 Créditos

Projeto realizado durante o evento **NLW Operator** da @Rocketseat, sob a instrução de @Arthur Kamienski.

---
Desenvolvido por [Seu Nome](https://github.com/seu-usuario) 🚀
