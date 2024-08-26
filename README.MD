# Cabeceras

# Cabecera H1

## Cabecera H2

### Cabecera H3

#### Cabecera H4

##### Cabecera H5

###### Cabecera H6

# Formatos Emphasis

- letra _italica_.
- Formato **bold o strong**.
- Formato ~~tachado~~.

# Listas

1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.

- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.
- Esto es un item de lista desordenada.

# Links

- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://google.com)

# Imagenes

![Logo GitHub](https://static.vecteezy.com/system/resources/thumbnails/017/119/660/small/github-logo-git-hub-icon-with-text-on-white-and-black-background-free-vector.jpg)

# Code Snippets

Highlights

Codigo en JavaScript

```
<script>
//final: array {dia, mes,año}
function diasHasta(final){
  let Hoy=new Date();
  let fin = new Date(final.año, final.mes, final.dia);
  let mseg_dia=1000*60*60*24;
  let dias ;
  if (Hoy.getMonth()==final.mes && Hoy.getDate()>final.dia) {
      fin.setFullYear(fin.getFullYear()+1) ;
  }
  dias = Math.ceil((fin.getTime()-Hoy.getTime())/(mseg_dia));
  let cuadro=document.getElementById('cuenta');
  cuadro.innerText="Faltan "+dias+" dias hasta "+fin.toLocaleDateString()
}
</script>
```

# Tablas

| Nombre | Apellido | Documento  |
| ------ | -------- | ---------- |
| Maxi   | Burgos   | 8237489027 |
| Tomas  | Thompson | 324262342  |

# Citas

Esto es un texto referente a la siguiente cita:

> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior.

> Esto es otra cita.

Fin.

# Lineas Divisorias

Un texto dividido por guiones normales.

---
