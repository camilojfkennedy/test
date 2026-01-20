:::{toctree}
:hidden:
:maxdepth: 2
:caption: TITULO 01

decimo.md
decimoGUIA01.md
:::

:::{toctree}
:hidden:
:maxdepth: 2
:caption: TITULO 02

octavo.md
README.md
:::

# NUEVA PLANTILLA reemplaza a la index.rst

## EN PRUEBAS

Presentación para Catalina Fonseca y Sandra Rabello:

![cata](cata.png)


1. Desde Puerto Boyacá


## campos
:External URL: [Explicit text](https://example.com)
:Internal target reference: [Explicit text](#callouts)
:Internal file reference: [Explicit text](#otros-callouts)
:Internal file -> heading reference: [Explicit text](#imagenes)
:Downloadable file: [Explicit text](tubo.png)

### Campo 01
`# sudo apt get install`

## Enlaces

Y ahora como se configuran los menús?

[PRESIONE ACA](index.md#enlaces)

[PRESIONE ACA 2](index.md#tablas-teclas)

[PRESIONE ACA 3](index.md#teniendo-en-cuenta-otra)

[INTERNET](https://www.google.com)

> "muestra una cita"

```python
print("hola")
```

```c++
cout << "hola" <<endl;
```

## Este seria un submenu
Tal vez...

## Matematicas
$$
X = \frac{12}{X}
$$

$X = Y^2$

## imagenes

![imagen](tubo.png){align=center}

:::{figure} tubo.png
:align: center
Caption this 
:::

## tablas-teclas

SHORTCUT | KEY
-|-
{kbd}`ctrl` + {kbd}`alt`  | {guilabel}`UI element`

## TASKLIST

- [ ] uno
- [ ] dos
- [X] tres

## Callouts

```{code-block}
---
emphasize-lines: 1
---
$ dnf install nano
```

```{danger}
OK run
```

```{warning}
CALLOUTS!!!

    print("hola mundo")

now yes?
```

:::{admonition} titulo
:class: tip
ok
:::

:::{admonition} CUIDADO
:class: error 
ok
```python
print("hello")
```
se 
:::

<!-- ```{terminal}
   :input: command
   :user: root
   :host: vampyr
   :dir: /home/user/directory/

the output
``` -->

## Teniendo en cuenta otra

## Otros callouts

:::{card} OFERTA
Investigación
^^^
Card content
+++
Palabra final
:::

::::{tab-set}
:::{tab-item} Python
Renombrar
:::
:::{tab-item} Python 2
Comenzar
:::
::::

# OTRO MENU

## Start