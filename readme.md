# Taller de Detección Sísmica con IA

## Guía de Instalación y Configuración

Este repositorio contiene el entorno y las herramientas necesarias para el taller de detección sísmica utilizando Inteligencia Artificial, mediante el uso de EQTransformer y GaMMA.

---

# Requisitos Previos

Antes de comenzar, asegúrese de tener instalados los siguientes programas:

- [Visual Studio Code (VSCode)](https://code.visualstudio.com/)
- Extensión Jupyter para VSCode
- Extensión Python para VSCode
- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)

---

# Instalación de Miniconda (Linux)

## Descargar Miniconda

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```

---

## Dar permisos de ejecución

```bash
chmod +x Miniconda3-latest-Linux-x86_64.sh
```

---

## Ejecutar el instalador

```bash
./Miniconda3-latest-Linux-x86_64.sh
```

Durante la instalación:

- Acepte los términos de licencia.
- Mantenga la ruta por defecto (recomendado).
- Seleccione `yes` cuando se pregunte si desea inicializar Conda automáticamente.

Al finalizar, cierre y vuelva a abrir la terminal.

---

## Verificar instalación

```bash
conda --version
```

---

# Creación de Ambientes Conda

El taller utiliza dos ambientes independientes:

- `eqt_gpu`: entorno para EQTransformer con soporte GPU.
- `gamma_env`: entorno para GaMMA.

---

## Crear ambiente para EQTransformer

```bash
conda env create -f eqt_gpu.yml
```

---

## Crear ambiente para GaMMA

```bash
conda env create -f gamma_env.yml
```

---

# Clonar EQTransformer

## Clonar repositorio oficial

```bash
git clone https://github.com/smousavi05/EQTransformer.git
```

Repositorio oficial:

https://github.com/smousavi05/EQTransformer

---
