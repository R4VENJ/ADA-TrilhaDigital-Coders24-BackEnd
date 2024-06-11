# ADA SANTANDER - Curso Digital
# Módulo 03 - Introdução ao Java

## 01 - Introdução ao Java
* FRONTEND é a parte que se interage;
* BACKEND é a parte que fica oculta interagindo com aplicações;
* FULLSTACK é a combinação dos dois.

### CMD
> java -version <br />
> jshell <br />
> System.out.println("Hello World"); <br />
> /exit

## 02 - Setup

### Downlooads
* https://www.oracle.com/java/technologies/downloads/
* https://www.jetbrains.com/idea/download/?section=windows
  
## 03 - Variáveis

* byte: The byte data type is an 8-bit signed two's complement integer. It has a minimum value of -128 and a maximum value of 127 (inclusive). The byte data type can be useful for saving memory in large arrays, where the memory savings actually matters. They can also be used in place of int where their limits help to clarify your code; the fact that a variable's range is limited can serve as a form of documentation.

* short: The short data type is a 16-bit signed two's complement integer. It has a minimum value of -32,768 and a maximum value of 32,767 (inclusive). As with byte, the same guidelines apply: you can use a short to save memory in large arrays, in situations where the memory savings actually matters.

* int: By default, the int data type is a 32-bit signed two's complement integer, which has a minimum value of -231 and a maximum value of 231-1. In Java SE 8 and later, you can use the int data type to represent an unsigned 32-bit integer, which has a minimum value of 0 and a maximum value of 232-1. Use the Integer class to use int data type as an unsigned integer. See the section The Number Classes for more information. Static methods like compareUnsigned, divideUnsigned etc have been added to the Integer class to support the arithmetic operations for unsigned integers.

* long: The long data type is a 64-bit two's complement integer. The signed long has a minimum value of -263 and a maximum value of 263-1. In Java SE 8 and later, you can use the long data type to represent an unsigned 64-bit long, which has a minimum value of 0 and a maximum value of 264-1. Use this data type when you need a range of values wider than those provided by int. The Long class also contains methods like compareUnsigned, divideUnsigned etc to support arithmetic operations for unsigned long.

* float: The float data type is a single-precision 32-bit IEEE 754 floating point. Its range of values is beyond the scope of this discussion, but is specified in the Floating-Point Types, Formats, and Values section of the Java Language Specification. As with the recommendations for byte and short, use a float (instead of double) if you need to save memory in large arrays of floating point numbers. This data type should never be used for precise values, such as currency. For that, you will need to use the java.math.BigDecimal class instead. Numbers and Strings covers BigDecimal and other useful classes provided by the Java platform.

* double: The double data type is a double-precision 64-bit IEEE 754 floating point. Its range of values is beyond the scope of this discussion, but is specified in the Floating-Point Types, Formats, and Values section of the Java Language Specification. For decimal values, this data type is generally the default choice. As mentioned above, this data type should never be used for precise values, such as currency.

* boolean: The boolean data type has only two possible values: true and false. Use this data type for simple flags that track true/false conditions. This data type represents one bit of information, but its "size" isn't something that's precisely defined.

* char: The char data type is a single 16-bit Unicode character. It has a minimum value of '\u0000' (or 0) and a maximum value of '\uffff' (or 65,535 inclusive).

---
https://github.com/R4VENJ/primeiro-projeto-java/blob/master/src/Main.java

## 04 - Operadores Booleanos | Tabela Verdade
https://github.com/R4VENJ/primeiro-projeto-java/blob/master/src/Boolean.java

## 05 - Estruturas Condicionais
https://github.com/R4VENJ/primeiro-projeto-java/blob/master/src/estruturaCondicional.java

## 06 - Manipulação de Strings e Datas
https://github.com/R4VENJ/primeiro-projeto-java/blob/master/src/manipulandoStrings.java

## 07 - Laços Numéricos
https://github.com/R4VENJ/primeiro-projeto-java/blob/master/src/lacosNumericos.java

## 08 - Vetores
https://github.com/R4VENJ/primeiro-projeto-java/blob/master/src/Vetores.java

## 09 - Funções
https://github.com/R4VENJ/primeiro-projeto-java/blob/master/src/Functions.java
