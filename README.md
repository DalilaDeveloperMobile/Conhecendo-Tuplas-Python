![Captura de tela 2024-04-17 123206](https://github.com/DalilaDeveloperMobile/Conhecendo-Linguagem-Python/assets/29806802/83eba503-c094-4431-b85f-e7b4cc9d92de)
### Passos Iniciais Realizados Nesse Bootcamp Python AI Backend Developer. [dio_me](https://www.dio.me/)
### ✅ Conhecendo Tuplas em Python.

### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Declarando Tuplas:
```
frutas = (
    "laranja",
    "pera",
    "uva",
)
print(frutas)

letras = tuple("python")
print(letras)

numeros = tuple([1, 2, 3, 4])
print(numeros)

pais = ("Brasil",)
print(pais)
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Acesso Direto:
```
frutas = ("maçã", "laranja", "uva", "pera",)

print(frutas[0])  # maçã
print(frutas[2])  # uva
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Indices Negativos:
```
frutas = (
    "maçã",
    "laranja",
    "uva",
    "pera",
)

print(frutas[-1])  # pera
print(frutas[-3])  # laranja
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Matriz:
```
matriz = (
    (1, "a", 2),
    ("b", 3, 4),
    (6, 5, "c"),
)

print(matriz[0])  # (1, "a", 2)
print(matriz[0][0])  # 1
print(matriz[0][-1])  # 2
print(matriz[-1][-1])  # "c"
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Fatiamento:
```
tupla = ("p", "y", "t", "h", "o", "n",)

print(tupla[2:])  # ("t", "h", "o", "n")
print(tupla[:2])  # ("p", "y")
print(tupla[1:3])  # ("y", "t")
print(tupla[0:3:2])  # ("p", "t")
print(tupla[::])  # ("p", "y", "t", "h", "o", "n")
print(tupla[::-1])  # ("n", "o", "h", "t", "y", "p")
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Iterar Tuplas:
```
carros = (
    "gol",
    "celta",
    "palio",
)

for carro in carros:
    print(carro)


for indice, carro in enumerate(carros):
    print(f"{indice}: {carro}")
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Count:
```
cores = (
    "vermelho",
    "azul",
    "verde",
    "azul",
)

print(cores.count("vermelho"))  # 1
print(cores.count("azul"))  # 2
print(cores.count("verde"))  # 1
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Index:
```
linguagens = ("python", "js", "c", "java", "csharp",)

print(linguagens.index("java"))  # 3
print(linguagens.index("python"))  # 0
```
### <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> Len:
```
linguagens = (
    "python",
    "js",
    "c",
    "java",
    "csharp",
)

print(len(linguagens))  # 5
```
<h3 align="center"> Made with <img src="https://gifs.eco.br/wp-content/uploads/2021/06/gifs-de-coracao-7.gif" width="30px"> by Dalila...</h3>
<div align="center"  style="display: inline-block">
  <a href="https://www.linkedin.com/in/dalila-cust%C3%B3dio-046076181/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  <a href = "mailto:dalila.dalila70@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://instagram.com/dalila.dalila70" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a target="_blank" href="https://api.whatsapp.com/send?phone=5588997138541"><img  alt="Whatsapp" width="117px" src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white"/></a> 
</div>




