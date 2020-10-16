# Primer-Parcial-Python
import math

"""
***************************************************************
@@ ejercicio 1 @@
un metodo python que haga la suma de 2 numeros
2+4 = 6
"""


# start-->
def suma(numero1, numero2):
    numero1 = numero1
    numero2 = numero2

    resultado = numero1 + numero2
    return resultado
    print (resultado)


"""
***************************************************************
@@ ejercicio 2 @@
la suma de los numeros pares del 1 al 1000
"""


# start-->
def sumaPares():
    m = 1
    n = 100
 
    print(sum(n for n in range(*sorted([m,n])) if not n & 1))

    result = 0
    return result


"""
***************************************************************
@@ ejercicio 3 @@
encontrar el area total de superficie de un cilindro
radio = 5 m
altura = 7 m
area lateral: 2*pi*r*a
area circulo: 2*pi*r^2
area total: area lateral + area circulo
"""


# start-->
def areaTotalCilindro(AreaTotal):
    AreaTotal = areaLateral + areaCirculo
    print (AreaTotal)
    result = 0
    return result


def areaLateral(altura, radio):
    altura = 7
    radio = 5
    areaLateral = 2*math.pi*radio*altura
    result = 0
    return result


def areaCirculo(radio):
    radio = 5
    areaCirculo = 2*math.pi*(radio*radio)
    result = 0
    return result


"""
***************************************************************
@@ ejercicio 4 @@
el ejercicio numero 3 convertirlo en una clase
"""


# start-->
class Cilindro:
    def areaTotalCilindro(self, radio, altura, AreaTotal, areaLateral, areaCirculo):
        self.__radio = 5
        self.__altura = 7
        self.__areaLateral = 2*math.pi* self.__radio * self.__altura
        self.__areaCirculo = 2*math.pi*(self.__radio * self.__radio)
        self.__AreaTotal = self.__areaLateral + self.__areaCirculo

        result = self.__AreaTotal

        print ("el area es: " +result)

        return result
        return 0


"""
***************************************************************
@@ ejercicio 5 @@
restaurante de pizzas
pizza
    nombre
    lugar
    costo
    conDescuento
    descuento
"""


class Restaurante:
    Restaurante = Restaurante()

    def ordenar(self, especialidad, lugar, costo, conDescuento, descuento):

        pass

    def costoTotal(self):
        return 0

    def costoTotalConDescuento(self):
        return 0


class Pizza:
    def pizza(self):
        self.Especialidad = ("Hawaiana", "Meat Lover", "Suprema", "Cuatro Quesos")


"""
***************************************************************
@@ ejercicio 6 @@
colocar este proyecto en github
colocar aca debajo la url
ademas colocar la url en un archivo
github_<nombre>_<codigo>.txt y subirlo a moodle
"""


# github url-->
def getGithubUrl():
    return "https://github.com/AlbertoCVillalta/Primer-Parcial-Python.git"
