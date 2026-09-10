# Primeiro Exercício

class Pessoa:

    def __init__(self, nome, idade):
        self.nome = nome
        self.idade = idade
      
Pessoa = Pessoa("Maria", 16)
print(Pessoa.nome)
print(Pessoa.idade)


# Segundo Exercício

class Produto1:

    def __init__(self, nome, preco, estoque):
        self.nome = nome
        self.preco = preco
        self.estoque = estoque
      
class Produto2:

    def __init__(self, nome, preco, estoque):
        self.nome = nome
        self.preco = preco
        self.estoque = estoque
      
Produto1 = Produto1("Escova de dente", 3.50, 3)
print(f"Nome produto: {Produto1.nome} ")
print(f"Preço: {Produto1.preco}")
print(f"Estoque: {Produto1.estoque}")

Produto2 = Produto2("Pasta de dente", 3.50, 4)
print(f"Nome produto: {Produto1.nome} ")
print(f"Preço: {Produto1.preco}")
print(f"Estoque: {Produto1.estoque}")


# Terceiro Exercício

class Aluno:

    def __init__(self, nome, nota):
        self.nome = nome
        self.nota = nota

Aluno1 = Aluno("Rodrigo Faro", 10)
print(f"Nome: {Aluno1.nome} ")
print(f"Nota: {Aluno1.nota} ")

nota = Aluno1.nota

if nota >= 6:
  print("Aluno Aprovado")

else:
    print("Aluno Reprovado")


# Quarto Exercício

class retangulo:

  def __init__(self, largura, altura):
        self.largura = largura
        self.altura = altura

  def calcular_perimetro(self, largura, altura):
        return  2 * (self.largura + self.altura)

retangulo = retangulo(5,10)
perimetro = retangulo.calcular_perimetro(2, 5)

print(f"largura: {retangulo.largura}")
print(f"altura: {retangulo.altura}")
print(f"perimetro: {perimetro}")


# Quinto Exercício

