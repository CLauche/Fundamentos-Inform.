# Fundamentos-Inform.
#ejercicio 1 del TP

class Elemento:
    def __init__(self,numeroAtomico,cantNeutrones,simbolo,valencia):
        self.__numeroAtomico = numeroAtomico
        self.__simbolo = simbolo
        self.__valencia = valencia
        self.__cantNeutrones = cantNeutrones

    def cantElectrones(self):
        return self.__numeroAtomico

    def cantProtones(self):
        return self.__numeroAtomico

    def pesoAtomico (self):
        return self.__numeroAtomico + self.__cantNeutrones


# para cada elemento agregado se ingresa la cantidad de neutrones que posee,/
#  de manera de facilitar el cálculo del pesoAtomico

oxigeno = Elemento(8,8,'O',2)
hidrogeno = Elemento (1,0,'H',1)
nitrogeno = Elemento(7,7,'N',5)
carbono = Elemento (6,6,'C',4)
azufre = Elemento (16,16,'S',6)


