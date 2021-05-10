# Optimización Avanzada: Práctica 2, Segunda Parte

## Integrantes y Roles

|Tarea | Integrantes | Usuario |
|:---:|:---:|:---:|
|Project Manager, Reporte|Lau|@ltejadal|
|Perfilamiento de Código|Santi|@santibatte|
|Tests, Automatización de lectura de datos|Rafa|@rafaelortegar |
|Reimplementación de Código, Documentación|Sebas|@C1587S|


## Descripción del Proyecto

 En esta parte de la práctica 2 se re-implementan en la librería (
[![ACO-TSP](https://gist.githack.com/C1587S/6f2fccb2473f9c9c8a093db7a03f9ab3/raw/f895b41f3ea45fd26c529b7e80ea4a3c69b0e0a5/ACO%20TSP%20pkg.svg)](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal)) los métodos que se escribieron originalmente, de manera que sean más eficientes en tiempo de ejecución. Los ejercicios de perfilamiento de la anterior implementación del algoritmo se presentan [aquí](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-ltejadal/tree/main/perfilamiento). La implementación con cómputo en paralelo se implementa en la librería y se explica en [este](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-ltejadal/blob/main/notebooks/eficiencia_codigo/reimplementacion_multiprocessing.ipynb) _notebook_, y [aquí](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-ltejadal/blob/main/notebooks/eficiencia_codigo/ejemplo_multiprocessing.ipynb) se presenta un ejemplo de su uso. Finalmente se incluye el [reporte](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-ltejadal/blob/main/reporte_equipo_4_parte_2_practica_2.ipynb) de la actividad ejecutado en `AWS`.

## Ejecución en [`Binder`](https://mybinder.org/)

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/optimizacion-2-2021-1-gh-classroom/practica-2-segunda-parte-ltejadal/main?urlpath=lab)

## Documentación

[![Documentation](https://img.shields.io/static/v1.svg?label=Documentation%20ACO-TSP&message=v1&color=blue)](https://optimizacion-2-2021-1-gh-classroom.github.io/practica-1-segunda-parte-ltejadal/)

## Imagen de Docker

[![Dockerfile](https://badges.aleen42.com/src/docker.svg)](https://hub.docker.com/r/santibatte/ant_colony_jupyter/tags?page=1&ordering=last_updated)

## Github Actions

[![sphinx-doc](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal/actions/workflows/sphinx-doc.yml/badge.svg)](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal/actions)

[![docker-image-build-and-push.yml](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal/actions/workflows/docker-image-build-and-push.yml/badge.svg)](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal/actions)

[![ci.yml](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal/actions/workflows/ci.yml/badge.svg)](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal/actions)


## Referencias

1. [Cómputo en paralelo usando CPUs en un sistema de memoria compartida (SMC)](https://itam-ds.github.io/analisis-numerico-computo-cientifico/V.optimizacion_de_codigo/5.4/Computo_en_paralelo_usando_CPUS_en_SMC.html#multiprocessing) (2021) Erick Palacios
2. [National Travelling Salesman Problems](https://www.math.uwaterloo.ca/tsp/world/countries.html) (2017) University of Waterloo
3. [aco_tsp_oo.py](https://github.com/optimizacion-2-2021-1-gh-classroom/practica-1-segunda-parte-ltejadal/blob/main/src/ant_colony/aco_tsp_oo.py) (2021) optimizacion-2-2021-1-gh-classroom
/
practica-1-segunda-parte-ltejadal

