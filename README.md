# Batalha Naval com Inteligência Artificial

Jogo de Batalha Naval desenvolvido em Python utilizando a biblioteca Pygame, com múltiplos níveis de dificuldade de IA.

## Funcionalidades

- Jogador vs Máquina
- Interface gráfica com Pygame
- Posicionamento manual de navios
- Posicionamento aleatório
- IA Fácil
- IA Média
- IA Difícil com Heatmap
- Reiniciar partida
- Menu de controles

---

# Tecnologias Utilizadas

- Python 3
- Pygame

---

# Pré-requisitos

Antes de executar o projeto, instale:

- Python 3.10 ou superior
- pip
- pygame

---

# 1. Instalar o Python

Baixe o Python no site oficial:

https://www.python.org/downloads/

Durante a instalação, marque a opção:

[x] Add Python to PATH

---

# 2. Verificar Instalação do Python

Abra o terminal e execute:

```bash
python --version
```

ou

```bash
py --version
```

Saída esperada:

```bash
Python 3.12.0
```

---

# 3. Verificar Instalação do pip

O pip normalmente já vem instalado com o Python.

Verifique com:

```bash
pip --version
```

Caso não funcione:

```bash
python -m ensurepip --upgrade
```

---

# 4. Criar Ambiente Virtual (venv)

O correto é "venv" (Virtual Environment).

Crie o ambiente virtual:

```bash
python -m venv venv
```

---

# 5. Ativar o Ambiente Virtual

## Windows

```bash
venv\Scripts\activate
```

## Linux / Mac

```bash
source venv/bin/activate
```

Quando ativado, o terminal ficará parecido com:

```bash
(venv)
```

---

# 6. Instalar as Bibliotecas

Instale o Pygame:

```bash
pip install pygame
```
# 7. Estrutura do Projeto

```plaintext
BatalhaNaval/
│
├── main.py
├── README.md
├── requirements.txt
└── venv/
```

---

# 8. Executar o Jogo

Dentro da pasta do projeto:

```bash
python main.py
```

ou

```bash
py main.py
```

---

# Controles do Jogo

| Tecla / Ação | Função |
|---|---|
| Mouse | Posicionar navios |
| Mouse | Atacar inimigo |
| R | Girar navios |
| ESC | Abrir/Fechar menu |
| Aleatório | Posiciona navios automaticamente |
| Novo Jogo | Reinicia a partida |

---

# Níveis de Dificuldade da IA

## Fácil
A IA realiza tiros aleatórios.

## Médio
Após acertar um navio, a IA tenta atacar posições adjacentes.

## Difícil
A IA utiliza um sistema de Heatmap para calcular as posições com maior probabilidade de conter navios.

---

# Como Funciona o Heatmap

A IA difícil cria um mapa de probabilidades baseado em:

- Tamanho dos navios restantes
- Possíveis posições válidas
- Histórico de tiros
- Acertos anteriores

A posição com maior pontuação é escolhida como próximo ataque.

---

# Instalar Dependências Automaticamente

Caso exista um arquivo requirements.txt:

```bash
pip install -r requirements.txt
```

---

# Erros Comuns

## Erro: No module named pygame

Solução:

```bash
pip install pygame
```

---

## Erro: python is not recognized

Solução:
Reinstale o Python e marque:

```plaintext
Add Python to PATH
```

---

# Melhorias Futuras

- Multiplayer online
- Sons e efeitos
- Sistema de pontuação
- Animações
- IA mais avançada
- Diferentes mapas

---

# Autores

Pedro Simões Pacheco
João

---

# Licença

Projeto desenvolvido para fins educacionais.
