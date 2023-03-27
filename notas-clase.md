minlength="6" expresion regular de input, funciona para poner un minimo de caracteres en los formularios, util para formularios de contrasenas  

maxlength="12" lo mismo que el de arriba pero con maximos 

                                contrasenas! 

para simplificar lo de arriba se usan "patrones" este es un parametro es similar a un molde echo a la medida con dieferentes condiciones a cumplir y tiene varias partes.
1.-  siempre empieza con el simbolo de acento circunflejo(flechita arriba) y termiona con el signo de pesos
2 .=  dentro de estos el parentesis indica las partes a evaluar
3.- el signo "?=" indica que aceptaremos caracteres(digitos, numeros, cualquier caracter en general)
4.- el "." impide que sean saltos de linea o enters 
5.- los asterriscos son un indicador de que debe haber al menos un caracter de los indicados a la derecha del asterisco en el ejemplo de abajo indica que debe haber al menos una minuscula y una mayuscula 
6.- los "?!" son para negar, en el ejemplo de abajo indica que NO debe haber espacios ni alguno de los caracteres puestos entre corchetes
7.-por ultimo el ".{}" indica cual es el minimo y maximo de caracteres que se pueden ocupar en la contsena 


pattern= "^(?=.*[a-z])(?=.*[A-Z])(?!.*[ !@#$%^&*()_+]).{6,12}$"

nosotros al programar sabemos todas estas condicionales, para que el usuario sepa como crear la suya tenemos que agregar la expresion regular title= "" donde podremos poner un texto que le informara como debe crear su contrasena


                                formulario cumpleaños

el input por defecto me dejara poner cualquier dato, para corregir esto en caso de necesitar una fecha especifica usaremos: type: "date" y nos mostrara el formato predefinido para fecha e incluzo un icono de calendario que permitira escoger la fecha

NOTA: "blur" tipo de evento, hace referencia a cuando se quita el foco de un espacio o input

.setCsutomValidity(mensaje) define el mensaje de validación para el elemento seleccionado con el mensaje especifico, ocupa una variable extra con el mensaje a mostrar 

input.dataset.tipo; dataset representa el arbol de datas que se han puesto en el codigo .tipo es la segunda parte del data creado

 data-fecha

 input.dataset.fecha

 input container invalid
 validiti

 mistmach

 innerhtml

 pattern="\d{10}" expresion regular para escribir solo nuimeros telefonicos


pattern="[\s\S]{10,40}"

fork en git hub pages hara una copia del codigo para que la pueda modificar


 