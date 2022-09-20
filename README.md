# Santiago Mondragon

Este repositorio tiene las prácticas y entregas de la materia de Sistemas Operativos y
Redes del parcial 1.

## Prácticas parcial 1

-[Instruciones](./README.md)

-[Practica 1](./Practica1.md)

-[Practica 2](./Practica2.md)

-[Practica 4](https://github.com/SantiDEV2/practica4)

-[Practica 8](./Practica8.md)

-[Parcial 2, Practica 1](https://github.com/SantiDEV2/Parcial-2-Pr-ctica-1)

Creando la version 1.0.0 de este repositorio

## Parcial 2 - Practicas 3

<br>

- ¿Cómo se inicializa un repositorio en Git?

Para inicializar un repositorio existente lo primero que tenemos que hacer es poner el comando init para crear el repositorio y despues colocarnos en la rama main:

```bash 
$git init
$git branch -M main
```

- ¿Cómo creas un repositorio en GitHub?

Primero tendras que iniciar secion en tu cuenta de github y en la parte de la derecha en el simbolo del mas aparecera una opcion para crear un nuevo repositorio

![img](https://media.discordapp.net/attachments/791128242194481153/1021798602886086776/unknown.png)

<br>

- ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

Para esto se usa el comando de en el cual tenemos que agregar el repositorio mediante la liga de url que nos proporciona este y apartir de ahi solo se usaria el comando git push para subir cambios del local al remoto

```bash
$git remote add origin https://github.com/usuario/repositorio.git
$git push -u origin main
```

- ¿Cuál es el flujo básico de trabajo en Git y GitHub?

Existen 4 etapas en este la **"Working Stage"** en esta es el remoto en el cual trabajaras todo el tiempo

Despues tenemos la etapa de **"Staging"** en esta los cambios que hayas hecho en la etapa anterior se prepararan para subir y para este se usa el comando de 

```bash
$git add .
```

La etapa de **"Local Repository"** es este estado los cambios ya se han registrado en el repositorio de Git y para este se usa el comando de 

```bash
$git commit -m "Prueba"
```

Y por ultimo la etapa **"Remota"** en esta todos los cambios hechos en las anteriores se subiran a nuestro repositorio remoto en la url de github que introducimos y para este su comando le corresponde a 

```bash
$git push -u origin main
```