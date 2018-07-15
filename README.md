# Platzom
Platzom es un idioma inventado para el Curso de Fundamentos de Javascript

## Descripción del idioma

- Si la palabra termina en ar, se le quitan esos dos caracteres
- Si la palabra inicia  con z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir por la mitad y unir con un guión del medio
- Si la palabra original es un palíndromo ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas

## Instalación

```
npm install platzom
```

## Uso

```
import platzom from 'platzom'

platzom("programar") // Program
platzom('zorro')
platzom('zarpar')
platzom('abecedario')
platzom('sometemos')
```
## Créditos
- [Saul Morales Pacheco](https://saulmoralespa.com)

## Licencia
[MIT](https://opensource.org/licenses/MIT)