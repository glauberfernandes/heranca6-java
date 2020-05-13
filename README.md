# Classes e métodos abstratos (abstract)

### Classes abstratas
* São classes que não podem ser instanciadas
* É uma forma de garantir herança total: somente subclasses não
abstratas podem ser instanciadas, mas nunca a superclasse abstrata

### Métodos abstratos
* São métodos que não possuem implementação.
* Métodos precisam ser abstratos quando a classe
é genérica demais para conter sua
implementação.
* Se uma classe possuir pelo menos um método
abstrato, então esta classe também é abstrata.
* Notação UML: *itálico*

### Exercício
Fazer um programa para ler os dados de N figuras (N fornecido
pelo usuário), e depois mostrar as áreas destas figuras na
mesma ordem em que foram digitadas.

### Diagrama de classes:
![UML_ExercicioResolvido2](https://github.com/glauberfernandes/heranca6-java/blob/master/UML_ExercicioResolvido2.PNG)
