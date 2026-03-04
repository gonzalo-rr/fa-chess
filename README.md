# FA-CHESS

## Sobre el proyecto

`Fa-Chess` es un analizador de ajedrez y una herramienta de aprendizaje táctico. Presenta una interfaz gráfica de usuario que permite importar partidas para analizar y resolver puzzles.

`Fa-Chess` se puede adaptar a tu elo actual y ayudarte a mejorar.

## Primeros pasos

### Prerequisitos

Para empezar necesitarás:

- [python](https://www.python.org/downloads/)

Recomendamos que ejecutes `Fa-Chess` en un entorno linux con un compositor de ventanas [wayland](https://wayland.freedesktop.org/).

También recomendamos instalar:

- [uv](https://docs.astral.sh/uv/getting-started/installation/)
- [git](https://git-scm.com/install/)
- [git-lfs](https://git-lfs.com/)
- [stockfish](https://stockfishchess.org/download/)

### Intalación

1. Clona el repositorio

```
git clone https://github.com/avances123/fa-chess.git
```

2. Crea el entorno virtual e instala las dependencias

```
uv venv
uv sync
```

3. Descarga los puzzles

```
git lfs fetch
git lfs checkout
```

4. Ejecuta la interfaz gráfica

```
python main.py
```

5. ¡Aprende y disfruta!

=================================

# FA-CHESS

## About the project

`Fa-Chess` is a chess game analyzer and tactical learning tool. It presents a graphical user interface that allows users to import games to analyze and puzzles to solve.

`Fa-Chess` can adapt to your current elo and help you improve.

## Getting started

### Prerequisites

To get started you will need:

- [python](https://www.python.org/downloads/)

We recommend that you run `Fa-Chess` in a linux environment with a [wayland](https://wayland.freedesktop.org/) window compositor.

It is also recommended to install:

- [uv](https://docs.astral.sh/uv/getting-started/installation/)
- [git](https://git-scm.com/install/)
- [git-lfs](https://git-lfs.com/)
- [stockfish](https://stockfishchess.org/download/)

### Intallation

1. Clone the repository

```
git clone https://github.com/avances123/fa-chess.git
```

2. Create virtual environment and install the dependencies

```
uv venv
uv sync
```

3. Download the puzzles

```
git lfs fetch
git lfs checkout
```

4. Run the user interface

```
python main.py
```

5. Learn and enjoy!


