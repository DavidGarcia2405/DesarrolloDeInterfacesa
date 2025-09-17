# DesarrolloDeInterfacesa

- Autor: David Garcia Iraola
- GitHub: https://github.com/DavidGarcia2405

---

## Breves apuntes de markdown

# #= h1
## ##= h2
### ###= h3
#### ####= h4 
##### #####= h5
###### ######= h6

---
# Listas

Lista desordenada se indica con guiones
- item 1
- item 2
  - item 2.1
  - item 2.2

Lista ordenada se indica con numeros
1. item 1
2. item 2
      1. item 2.1
      2. item 2.2  

- [x] Hacer la cena 🧑‍🍳
- [ ] Ducharse 🚿
- [ ] Estudiar  👨‍🎓
- [ ] Hcer la cama 🛏️

---
## Estilos de texto
**Negrita** o __Negrita__

*Cursiva* o _Cursiva_

~Tachado~

**Negrita y dentro de una _Cursiva_**

Esto es un <sub>subindice</sub>

Esto es un <sup>superindice</sup>

Esto es un <ins>subrayado</ins>

> Esto es una cita o quote
>

Este tipo de callouts no funcionan en github

---

# Codigo preformateado y Codigo fuente

```

Esto es un texto preformateado
```
Este es el comando para iniializar un repositorio de git: `git init` ¿Te ha gustado el truco?

Y esto es un ejemplo en Python:
```python
saludo = 'Hola mundo!'
print(saludo)
```

# Claramente 
![Perros](https://www.hola.com/mascotas/20190423141017/razas-de-perro-raras/)

Enlazo una nota al pie [^1]
Enlazo una nota al pie [^nota]

[^1] Esta es una nota al pie
[^nota] Esta es otra nota al pie 

| Alieneacion izq | Alineacion medio | Alineacion derch |
| :--- | :---: | ---: |
| Dato1 | Dato2 | Dato3 |
| Dato4 | Dato5 | Dato6 |
<details>
  <summary>Este es el resumen de la seccion desplegable
    
  </summary>
    Un texto es una composición de signos codificados en un sistema de escritura que forma una unidad de sentido. También es una composición de caracteres imprimibles (con grafema) generados por un algoritmo de cifrado que, aunque no tienen sentido para cualquier persona, sí puede ser descifrado por su destinatario original. En otras palabras, un texto es un entramado de signos con una intención comunicativa que adquiere sentido en determinado contexto.
</details>
<details>
  <summary>
    ¿Cual es la sintaxis Python para imprimir por pantalla?

  </summary>

```python
print( 'texto' )
</details>

graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
</details>
