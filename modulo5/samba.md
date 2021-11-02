# Manual de Instalación y Configuración de SAMBA

  

### THE ULTIMATE GUIDE

  

> Este manual está dirigido a los vagos

  

***Créditos:***

A mi esfuerzo exhaustivo de búsqueda de Internet

*Este manual es incomparable*

  

```bash
$ sudo xd
```
![samba imagen](https://www.solvetic.com/uploads/tutorials/monthly_08_2017/c56fd49ee11390586c02acc0975c33a4.png)

Indice
1. [Introducción a SAMBA](#introduccion)
2. [Instalación](#instalacion)

## Introducción
### ¿Qué es SAMBA?
Es un conjunto de aplicaciones Linux, basada en el protocolo SMB[^1], que permite compartir archivos en red.

### Orígenes
Fue creado por [Andrew Tridgell](https://es.wikipedia.org/wiki/Andrew_Tridgell).
El necesitaba montar un espacio en disco en su computadora para un servidor Unix. 

Esa computadora utilizaba el sistema de archivos **NFS** (*Network File System*). Sin embargo, una aplicación necesitaba soporte para el protocolo **NetBIOS[^2]** (no soportado por el NFS).

Tridgell lo solucionó escribiendo un sniffer[^3] que permitía analizar el tráfico de datos generado por el protocolo NetBIOS. Hizo [ingeniería inversa](https://es.wikipedia.org/wiki/Ingenier%C3%ADa_inversa) en el protocolo SMB y lo implementó en el Unix.

Eso hizo que el servidor Unix apareciera como un servidor de archivos Windows en su PC con DOS.

[^1]: Server Message Block
[^2]: Network Basic Input/Output System
[^3]: Pequeño programa para captura de tráfico de datos en red

## Instalación

## Configuración

## Desinstalación