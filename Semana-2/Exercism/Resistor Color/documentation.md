1. RESISTOR COLOR

'export' hace que 'COLORS' sea accesible fuera del modulo.
Se define una variable constante llamada 'COLORS' y dentro se agrega una coleccion de datos 'negro, marrón, rojo, naranja, amarillo, verde, azul, violeta, gris, blanco'.

La segunda linea se define una constante 'colorCode' con parametro 'Color' de tipo string, y en la tercera linea regresa el valor de indice 'indexof' de 'COLORS' dependiendo que valor se introdujo en el parametro 'Color'

2. RESISTOR COLOR DUO

'enum ResistoValues' Enumera y se define los valores con los colores asociados, se declara un tipo 'Color' y se agrega un keyof y typeof para obtener las claves de 'ResistoValues'.

Se agrega una funcion: 'function decodedValue([first, second]: Color[]): number {
  return Number(`${ResistorValues[first]}${ResistorValues[second]}`)
}' 

Donde 'decodedValue' toma dos elementos 'first, second' de tipo 'Color'  y devuelve un número que representa el valor de resistencia decodificado.