# Código

Scripts en Python usados en el Anexo B del TFG para los cálculos de bifurcaciones y del coeficiente de Lyapunov del modelo de FitzHugh-Nagumo.

- [`TFG.ipynb`](TFG.ipynb) — notebook original (Google Colab) con las celdas de cálculo y su salida.
- [`tfg.py`](tfg.py) — mismo contenido exportado como script `.py`.

## Qué calcula

1. **Clasificación de puntos de equilibrio**: resuelve la ecuación cúbica de equilibrio del sistema y clasifica cada raíz real (Silla, Atractor, Repulsor, Neutro) a partir de los valores propios de la matriz Jacobiana.
2. **Primer coeficiente de Lyapunov l1**: usando `sympy`, deriva simbólicamente el sistema en el origen (derivadas de 2º y 3er orden) y calcula l1 para el caso general y para los casos particulares `b = 0` y `c = 0`, necesarios para determinar la supercriticidad/subcriticidad de la bifurcación de Hopf.

## Dependencias

```bash
pip install numpy sympy
```
