# RobotsVote: Do Robots Influence your vote 

# Setup rápido — Python 3.11 + Jupyter

## 1. Instalar Python 3.11

Download:

https://www.python.org/downloads/

Verificar:

```bash
python --version
```

---

## 2. Criar ambiente virtual

```bash
py -3.11 -m venv venv
```

Ativar:

### Windows

```bash
venv\Scripts\activate
```

### Linux / macOS

```bash
source venv/bin/activate
```

---

## 3. Instalar dependências

Instalar:

```bash
pip install -r requirements.txt
```

---



## 4. Abrir Jupyter

```bash
jupyter notebook
```

Abrir:

```text
robots_vote_support.ipynb
```

## 5. Se for necessário especificar o kernel para o jupyter
```bash
py -3.11 -m ipykernel install --user --name=robots_env --display-name "Python 3.11 (robots_env)"
```
