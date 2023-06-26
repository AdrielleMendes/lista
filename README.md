# lista
from _typeshed import Self
from estrutura_elementar import estrutura_elementar


class ArrayList(estrutura_elementar):
    def __init__(self):
        self.elemento=[]
        pass 
    

    def esta_vazio(self) -> bool:
        if len(self.elemnto)==0:
         return True
        else:
         return False
     

    def inserir(self, item):
        self.elemento.append(item)
        pass

    def remove(self, item):
        if item in self.elemento:
            self.elemento.remove(item)
        pass

    def tamanho(self) -> int:

        return 1

    def limpa(self):
        self.elemento=[]
        pass
    

    def procura(self, item) -> bool:
        if len(self.elemento)>0:
            return True
        else:
         return False

    def indice_de(self, item):
        if item in self.elemento:
           return self.elemento.index(item)
        else:
         return 1

    def recupera_indice(self, index):
        for item in self.elemento(item):
           if item == 00:
              return index 
        return 1
