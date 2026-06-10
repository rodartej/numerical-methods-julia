# Numerical Methods in Julia

> Notebooks de métodos numéricos en Julia: métodos iterativos para sistemas lineales y aproximación polinomial.

[![Julia](https://img.shields.io/badge/Julia-1.11-9558B2?logo=julia&logoColor=white)](https://julialang.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## Índice

| # | Carpeta | Tema | Notebooks |
|---|---------|------|-----------|
| 01 | [`01_metodos_iterativos/`](01_metodos_iterativos/) | Método de Jacobi para sistemas lineales | 1 |
| 02 | [`02_aproximacion_polinomial/`](02_aproximacion_polinomial/) | Chebyshev, Legendre, regresión y linealización | 4 |
| 03 | [`03_examen/`](03_examen/) | Examen integrador | 1 |

## Stack

- **Julia 1.11**
- **Álgebra lineal**: LinearAlgebra
- **Visualización**: Plots.jl
- **Numérico**: Statistics, Random

## Setup

```bash
git clone https://github.com/rodartej/numerical-methods-julia.git
cd numerical-methods-julia
```

Requiere [Julia 1.11+](https://julialang.org/downloads/) y el kernel de Jupyter `IJulia`:

```julia
using Pkg
Pkg.add("IJulia")
```

Luego:

```bash
jupyter lab
```

## Estructura

```
numerical-methods-julia/
├── README.md
├── LICENSE
├── .gitignore
└── NN_<tema>/
    └── *.ipynb
```

## Highlights

**Métodos iterativos** ([`01_metodos_iterativos/`](01_metodos_iterativos/))
Implementación del método de Jacobi para sistemas lineales.

**Aproximación polinomial** ([`02_aproximacion_polinomial/`](02_aproximacion_polinomial/))
Polinomios de Chebyshev y Legendre, regresión polinomial y linealización de modelos no polinomiales.

## Contexto académico

Material de la materia de Métodos Matemáticos / Modelado Computacional (CdD 5).

## Licencia

MIT — ver [LICENSE](LICENSE).

## Autor

**Jesús Eduardo Rodarte Rosales**
[GitHub](https://github.com/rodartej) · [LinkedIn](https://www.linkedin.com/in/jesusrodarte/) · jesusrod254@gmail.com
