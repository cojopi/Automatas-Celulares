<br />
<p align="center">
  <h3 align="center">Aplicación de Autómatas Celulares Evolutivos para el filtrado y la reconstrucción de imágenes corrompidas por ruido</h3>

  <p align="center">
    Proyecto final de la materia de Modelación y Simulación de Sistemas a cargo de la Ing. Marcy Helen Dorado Reynolds conformado por los estudiantes de Ingeniería de Sistemas de 7mo Semestre de la Escuela Militar de Ingeniería Unidad Académica Santa Cruz.
  
  1. Est. Fernando Belaunde Tercero
  2. Est. Juan Pablo Nuñez Molina
  3. Est. Iver Uwil Cuellar Rojas
  4. Est. Christian Andrés Ojopi Meyer
</p>

<details open="open">
  <summary>Tabla de Contenido</summary>
  <ol>
    <li>
      <a href="#Resumen">Resumen</a>
    </li>
    <li>
      <a href="#InformacionGeneral">Información General</a>
      <ul>
        <li><a href="#Introduccion">Introducción</a></li>
        <li><a href="#Objetivos">Objetivos</a></li>
      </ul>
    </li>
    <li><a href="#Proyecto">Proyecto</a></li>
    <li><a href="#Acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

## Resumen

Con el avance de las tecnologías y desarrollos en el área de los autómatas celulares evolutivos, surgen diferentes algoritmos que nos permiten usarlos en diferentes áreas como la biología, química, física, ingeniería de sistemas, entre otros, en la modelación y simulación de sistemas como el modelado de flujo de tráfico y peatones, el modelado de fluidos, el modelado de gases, el modelado de células y otros organismos, el modelado de percolación de fluidos, entre otros.
Una de estas aplicaciones es el procesamiento de imágenes modelando una imagen cualquiera como un sistema compuesto de células que representan los pixeles y sus niveles de RGB, y basando las reglas del autómata celular en los gradientes de la imagen.
En este documento exploraremos la posibilidad de realizar la reconstrucción de imágenes corrompidas por fuentes de ruido ya sea debido al paso del tiempo, perdida de información, entre otros, aplicando los algoritmos de redes neuronales, y ayudando a diferentes áreas como la investigación criminal, arte, ciencia, etc.

## Información General

### Introducción

El siguiente proyecto apunta a desarrollar un programa que permita al usuario entrenar un modelo en TensorFlow por medio de Keras con el objetivo de tener un modelo resistente al ruido y otras formas de perturbaciones, y permitir la regeneración de las imágenes a su estado original o aproximadamente original. Uno de los principales retos en el proyecto es la gran cantidad de características individuales que tiene cada objeto o ser, lo que dificulta poder regenerar imágenes conservando todas las características mediante un modelo general

### Objetivos

1. Objetivo General
   * Desarrollo de un autómata celular evolutivo con algoritmos de redes neuronales para la reconstrucción de imágenes corrompidas por diversas fuentes de ruido

2. Objetivos Especificos
   * Restaurar imágenes a un estado cercano al original
   * Posibilitar la reconstrucción de rostros

## Proyecto

El proyecto se encuentra en un <a href="https://colab.research.google.com/drive/1uDUtMWHaVzIlgVH7rJzaLINOerdey8Tb#scrollTo=i5wi_r4gyzFr"><strong>Notebook de Google Colaboratory</strong></a>

## Acknowledgements

* [Basado en la investigación Growing Neural Cellular Automata](https://distill.pub/2020/growing-ca/)
