# 🤖 Projeto de Machine Learning - Classificação de Personalidade (Extrovert vs Introvert)

Este projeto implementa uma esteira completa de aprendizado de máquina para classificação de personalidade (Extrovertido ou Introvertido) usando o dataset ["Extrovert vs Introvert Behavior Data"](https://www.kaggle.com/datasets/rakeshkapilavai/extrovert-vs-introvert-behavior-data).

## 📋 Requisitos do Sistema

- Python 3.8 ou superior
- Git (opcional, para clonar o repositório)
- Jupyter Notebook ou VS Code com extensão Python

## 🚀 Instalação e Configuração

### 📥 1. Obtendo o Projeto

#### Opção A: Download direto

- Baixe os arquivos do projeto diretamente
- Extraia em uma pasta de sua escolha

#### Opção B: Clone via Git (se disponível)

```bash
git clone <url-do-repositorio>
cd projeto2-personality
```

### 🔧 2. Configuração do Ambiente Virtual

O uso de ambiente virtual é **altamente recomendado** para evitar conflitos entre dependências.

#### 🪟 Windows

**PowerShell:**

```powershell
cd projeto2-personality
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

**Command Prompt (CMD):**

```cmd
cd projeto2-personality
python -m venv .venv
.\.venv\Scripts\activate.bat
python -m pip install --upgrade pip
pip install -r requirements.txt
```

#### 🐧 Linux / 🍎 macOS

```bash
cd projeto2-personality
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

### 📦 3. Dependências Instaladas

O arquivo `requirements.txt` inclui:

- **pandas** - Manipulação de dados
- **numpy** - Computação numérica
- **matplotlib** - Visualizações
- **scikit-learn** - Machine Learning

> **Obs:** Se não houver um `requirements.txt`, instale manualmente:
> 
> ```bash
> pip install pandas numpy matplotlib scikit-learn
> ```

## 🎯 Executando o Projeto

### 📓 Opção 1: Jupyter Notebook

```bash
# Com o ambiente virtual ativado, inicie o Jupyter
jupyter notebook
```

1. Abra o arquivo `esteira_aprendizado_personality.ipynb`
2. Execute as células sequencialmente (Shift + Enter)

### 💻 Opção 2: VS Code

1. Abra o VS Code na pasta do projeto:

   ```bash
   code .
   ```

2. Instale a extensão Python do VS Code (se não tiver)
3. Abra o arquivo `esteira_aprendizado_personality.ipynb`
4. Selecione o interpretador Python do ambiente virtual:
   - Pressione `Ctrl + Shift + P`
   - Digite "Python: Select Interpreter"
   - Escolha o Python da pasta `.venv`
5. Execute as células clicando no botão "Run" ou usando `Shift + Enter`

## 🔍 Estrutura do Projeto

```
projeto2-personality/
├── esteira_aprendizado_personality.ipynb  # Notebook principal
├── personality_dataset.csv                # Dataset utilizado
├── README.md                              # Este arquivo
└── .venv/                                 # Ambiente virtual (criado após setup)
```

## 📊 O que o Projeto Faz

### 🎯 Objetivo

Classificar o perfil de personalidade (Extrovertido ou Introvertido) com base em dados comportamentais.

### 🔄 Metodologia (9 Etapas)

1. **📥 Dataset Kaggle**: Extrovert vs Introvert Behavior Data
2. **📊 Estatísticas Descritivas**: Análise exploratória dos dados
3. **🔄 Transformação em Colunas**: Normalização e codificação de variáveis categóricas
4. **🧹 Transformação em Linhas**: Remoção de duplicatas
5. **📂 Divisão em 3 Conjuntos**: Treino, Validação, Teste
6. **🤖 Treinamento**: Modelo Random Forest
7. **📈 Avaliação**: Matriz de confusão e acurácia
8. **🔮 Predição**: Exemplo prático com amostra do conjunto de teste
9. **📝 Documentação**: Comentários e explicações no notebook

## 🎓 Resultados Esperados

- **Acurácia**: ~90% (pode variar conforme o split)
- **Modelo**: Random Forest
- **Visualizações**: Matriz de confusão

## 🛠️ Resolução de Problemas

### ❌ Erro: "Module not found"

- Certifique-se de que o ambiente virtual está ativado
- Reinstale as dependências: `pip install -r requirements.txt`

### ❌ Jupyter não abre

- Instale o Jupyter: `pip install jupyter`
- Ou use o notebook do VS Code

## 🔄 Desativando o Ambiente Virtual

Quando terminar de usar o projeto:

```bash
deactivate
```

## 📄 Licença

Este projeto é para fins educacionais e de aprendizado em Machine Learning.

---
# Video:

https://youtu.be/F01EOzRTkZs
