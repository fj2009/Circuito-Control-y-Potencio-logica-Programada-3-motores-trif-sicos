# Circuito-Control-y-Potencio-logica-Programada-3-motores-trifasicos

![Uploading Captura de pantalla 2026-11-09 101348.png…]()

## Descripción del proyecto

Este proyecto consiste en la programación de un sistema de arranque secuencial para tres motores trifásicos de jaula de ardilla mediante un autómata programable **Siemens LOGO!**.

El objetivo es automatizar el encendido de los motores por etapas, utilizando temporizadores y elementos de protección para controlar la instalación.

## Funcionamiento del programa

La secuencia de funcionamiento es la siguiente:

1. Al pulsar el botón de marcha, se activa el primer motor mediante el contactor KM1.
2. Después de 4 segundos, se activa el segundo motor mediante KM2, manteniéndose el primero en funcionamiento.
3. Transcurridos otros 3 segundos, se activa el tercer motor mediante KM3. Los tres motores permanecen encendidos.
4. Una vez completados los 10 segundos de funcionamiento, el sistema detiene los tres motores automáticamente.

El sistema también dispone de una parada de emergencia y de protecciones térmicas para detener la instalación en caso de fallo.

## Elementos utilizados

- Autómata programable Siemens LOGO!
- Tres motores trifásicos de jaula de ardilla.
- Tres contactores: KM1, KM2 y KM3.
- Pulsador de marcha.
- Pulsador de paro o emergencia.
- Relés térmicos de protección.
- Temporizadores internos del programa LOGO!.

## Archivo incluido

| Archivo | Descripción |
|---|---|
| `Esquema logo P2.lsc` | Programa de automatización realizado en LOGO! Soft Comfort. |

## Software utilizado

- **LOGO! Soft Comfort:** diseño y programación de la lógica de control.
- **Siemens LOGO!:** autómata programable utilizado para ejecutar la secuencia.

## Objetivos de la práctica

- Programar el arranque secuencial de tres motores.
- Utilizar temporizadores para controlar los tiempos de activación.
- Controlar varias salidas mediante lógica programada.
- Incorporar sistemas de parada y protección.
- Comprobar el funcionamiento de una automatización industrial mediante un autómata LOGO!.

---

**Proyecto realizado como parte de las prácticas del Grado Medio de Instalaciones de Telecomunicaciones – IES Caura.**
## Descripción del proyecto

Este proyecto consiste en la programación de un sistema de arranque secuencial para tres motores trifásicos de jaula de ardilla mediante un autómata programable **Siemens LOGO!**.

El objetivo es automatizar el encendido de los motores por etapas, utilizando temporizadores y elementos de protección para controlar la instalación.

## Funcionamiento del programa

La secuencia de funcionamiento es la siguiente:

1. Al pulsar el botón de marcha, se activa el primer motor mediante el contactor KM1.
2. Después de 4 segundos, se activa el segundo motor mediante KM2, manteniéndose el primero en funcionamiento.
3. Transcurridos otros 3 segundos, se activa el tercer motor mediante KM3. Los tres motores permanecen encendidos.
4. Una vez completados los 10 segundos de funcionamiento, el sistema detiene los tres motores automáticamente.

El sistema también dispone de una parada de emergencia y de protecciones térmicas para detener la instalación en caso de fallo.

## Elementos utilizados

- Autómata programable Siemens LOGO!
- Tres motores trifásicos de jaula de ardilla.
- Tres contactores: KM1, KM2 y KM3.
- Pulsador de marcha.
- Pulsador de paro o emergencia.
- Relés térmicos de protección.
- Temporizadores internos del programa LOGO!.

## Archivo incluido

| Archivo | Descripción |
|---|---|
| `Esquema logo P2.lsc` | Programa de automatización realizado en LOGO! Soft Comfort. |

## Software utilizado

- **LOGO! Soft Comfort:** diseño y programación de la lógica de control.
- **Siemens LOGO!:** autómata programable utilizado para ejecutar la secuencia.

## Objetivos de la práctica

- Programar el arranque secuencial de tres motores.
- Utilizar temporizadores para controlar los tiempos de activación.
- Controlar varias salidas mediante lógica programada.
- Incorporar sistemas de parada y protección.
- Comprobar el funcionamiento de una automatización industrial mediante un autómata LOGO!.

---

**Proyecto realizado como parte de las prácticas del Grado Medio de Instalaciones de Telecomunicaciones – IES Caura.**
