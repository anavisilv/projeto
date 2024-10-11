# lista_de_borboletas.py

class Borboleta:
    def __init__(self, nome, especie, cor):
        self.nome = nome
        self.especie = especie
        self.cor = cor

    def mostrar_info(self):
        return f"{self.nome} é uma borboleta da espécie {self.especie} e sua cor é {self.cor}."


def main():
    borboletas = [
        Borboleta("Monarca", "Danaus plexippus", "laranja e preto"),
        Borboleta("Cecropia", "Hyalophora cecropia", "vermelho e amarelo"),
        Borboleta("Azul", "Ithomia", "azul"),
    ]

    for borboleta in borboletas:
        print(borboleta.mostrar_info())


if __name__ == "__main__":
    main()
