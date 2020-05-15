#Platzom

Platzom es un idioma investado para el [Curso de Fundamentos de Javascript](https://platzi.com/js) de [Plazi](https://platzi.com), el mejor lugar de educacion online

##Descripcion del idioma

-Si la palabra termina en "ar", se le quitan esas dos letras

-Si la palabra inicia con Z, se la añade "pe" al final

-Si la palara traducida tiene 10 o mas letras, de debe partir en dos por la mitad y unir con un guion medio

-Por ultimo, sila palabra origial es un palíndromo, nnguna regla anterior cuenta y se devuelve la misma palabra pero intercalando letras mayúsculas y ninúsculas  

## Instalación


```
npm install platzom
```

## Uso 
```
import platzom from 'platzom'

platzom("Programar") //Program
platzom("Zorro") //Zorrope
platzom("Zarpar") //Zarppe
platzom("abecedario") //abece-dario
platzom("Sometemos") //SoMeTeMoS
```
##Créditos 
- [Madelen Azocar]

#Licencia 

[MIT](htpps://opensourse.org/licenses/MIT)