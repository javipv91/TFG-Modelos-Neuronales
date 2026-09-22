# Modelos Neuronales a través de Ecuaciones Diferenciales

Trabajo de Fin de Grado — Grado de Matemáticas, Escola Politècnica Superior, Universitat de les Illes Balears (UIB). Curso académico 2025-26.

**Autor:** Javier Peña Vior
**Tutora:** Dra. María Jesús Álvarez Torres

## Resumen

El objetivo principal de este Trabajo de Fin de Grado es estudiar el comportamiento de las neuronas usando las matemáticas. En lugar de buscar fórmulas exactas, se utiliza la teoría cualitativa para entender de forma visual y general cómo cambia la actividad de la neurona con el paso del tiempo.

El trabajo empieza explicando las bases biológicas para ver a la neurona como un sistema dinámico. Como el modelo original de Hodgkin-Huxley es muy complicado y tiene cuatro ecuaciones, se pasa al modelo de FitzHugh-Nagumo (FHN), que solo usa dos. Esta simplificación ayuda a ver claramente cómo interactúan la activación y la recuperación de la neurona, sin perder la esencia de lo que ocurre en la realidad biológica.

A lo largo del documento se analizan los puntos de equilibrio del sistema y se estudian las bifurcaciones (Silla-Nodo, Pitchfork y Hopf), demostrando que pequeños cambios en los valores iniciales del modelo pueden transformar por completo cómo actúa la neurona — por ejemplo, pasar de estar en reposo a disparar señales eléctricas sin parar, formando un ciclo límite.

Además, se aplica una teoría que separa el problema en dos velocidades (sistemas slow-fast): los procesos rápidos (cuando la neurona dispara la señal) y los lentos (cuando se recupera), lo que permite visualizar por qué ocurren esos "saltos" bruscos de energía. Para asegurar que los cálculos matemáticos son correctos, se han creado programas en Python que ayudan con las cuentas más difíciles, como el cálculo del coeficiente de Lyapunov.

## Contenido de la memoria

1. Fundamentos biológicos de la neurona
2. Conceptos básicos de las Ecuaciones Diferenciales Ordinarias (teoría cualitativa, bifurcaciones: Silla-Nodo, Pitchfork, Hopf)
3. Estudio de la ecuación de FitzHugh-Nagumo
4. Estudio de la ecuación de FitzHugh-Nagumo mediante sistemas Slow-Fast
5. Conclusiones
- Anexo Teórico
- Cálculos y códigos Python
- Demostraciones adicionales y ejemplos

**Palabras clave:** Ecuaciones diferenciales, Bifurcaciones, Modelos neuronales, Ecuación de FitzHugh-Nagumo, Sistemas lento-rápido

## Estructura del repositorio

- [`memoria/`](memoria) — memoria completa del TFG en PDF
- [`video/`](video) — simulación de excitación vs. recuperación neuronal
- [`codigo/`](codigo) — scripts Python usados para los cálculos del Anexo B (bifurcaciones, coeficiente de Lyapunov)
