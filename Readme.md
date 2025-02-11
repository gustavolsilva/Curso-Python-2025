# Curso de Python - 2025
**Instrutor:** Teo Calvo
**Onde?:** (Twitch](https://www.twitch.tv/teomewhy) ou [Youtube](https://www.youtube.com/@teomewhy)

## Dia 01
### Python
- Linguagem de programação criada em 1991 por Guido Van Rossum
- Linguagem de proposito geral
- Versátil
- Alto Nível
- Open Source
- Multiplataforma
- Facil de aprender (ensino de programação para crianças)
- Muito utilizada para área de Dados e pesquisa científica

### Instalação

- Python puro (https://www.python.org)

- Python com pacotes de Data Science: Anaconda (https://www.anaconda.com/download/success)

- Interface de desenvolvimento (IDE): Visual Studio Code (https://code.visualstudio.com/download)

### Primeira Função Python

Print: função de exibição em tela.

```
print("Olá mundo!!")
```

Para executar o programa, no terminal (se Windows o cmd, se no Linux e Mac o bash), dentro da pasta coloca o comando iniciando com a palavra chave ```python <nome_do_script.py>```<br>
```python ola_mundo.py```

Colocando outro comando 
```
print("Que dia bom!")
```
Salvando, e executando novamente ```python ola_mundo.py``` ele mostrará em tela *Ola mundo!!* e na linha seguinte *Que dia bom!*

Mais um comando

```
print("Meu nome é Teo!!")

```
Salvando, e executando novamente ```python ola_mundo.py``` ele mostrará em tela *Ola mundo!!* e na linha seguinte *Que dia bom!* e em seguida, *Meu nome é Teo!!*

### Comentários

Quando usamos a # (tralha, hashtag, jogo da velha), usamos para referenciar um comentário de linha única

```
# Este é um exemplo de comentário
```

### Interactive Session (Modo Interativo)
Um Comentário especial para ativar a Sessão Interativa e isso é um precedente de (Cerquilha espaço e dois sinais de porcento)

Do lado esquerdo haverá o botão de complementos e precisa procurar e instalar o **Jupyter**.

Após, o comando funcionará 

```
# %% 
print("Olá Mundo!!")

# %%
# Este é um outro comentário
print("Que dia bom!")
print("Meu nome é Gustavo!")
```

### Python para operações numéricas
```
# %%

# SOMA
print("1 + 1 =", 1 + 1 )

# SUBTRAÇÃO
print("10 - 5 =", 10 - 5)

# %%

# MULTIPLICAÇÃO
print("10 * 5 =", 10 * 5)

# DIVISÃO
print("10 / 3 =", 10 / 3)

# DIVISÃO COM INTEIRA PARTE
print("10 // 3 =", 10 // 3)

# RESTO DA DIVISÃO
print("10 % 4 =", 10 % 4)

# %%

# POTÊNCIA
print("3 ** 4 =", 3 ** 4)
```

### Variáveis
Sejam como Post-its.
Se você tem um objeto que você quer buscar depois, por exemplo, um pote de vidro que contém picles, ou pimentas. E você anota para registrar este item.

E no Python as variáveis se comportam semelhante.

Eu poderia definir uma variável significando o conteúdo.
```
nome = "Gustavo Lourenço"
```
Em resumo, você atribue a que você quer determinar e ele armazena em memória no computador para utilização.