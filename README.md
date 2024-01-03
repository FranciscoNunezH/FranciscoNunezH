
<h1>Hola 👋, Soy Francisco Nuñez</h1>

![](https://komarev.com/ghpvc/?username=FranciscoNunezH)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Code-JavaScript-informational?style=flat&logo=javascript&logoColor=white&color=6aa6f8)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=6aa6f8)


```python
class Perfil:
    def __init__(self, nombre, titulo, habilidades, nivel_idioma):
        self.nombre = nombre
        self.titulo = titulo
        self.habilidades = habilidades
        self.nivel_idioma = nivel_idioma

    def crear_biografia(self):
        biografia = (
            f"👋 ¡Hola, soy {self.nombre}! {self.titulo} apasionado por la programación y la tecnología. Mis habilidades incluyen:  {self.habilidades}. "
            f"¡Conéctemos y colaboremos! 💻 #TechEnthusiast #Programming #Developer #DataAnalyst #CodeNewbie #CodingCommunity #Django"
        )
        return biografia

mi_perfil = Perfil(
    nombre="Francisco Nuñez Hernandez",
    titulo="Desarrollador Python 🐍",
    habilidades="Python, Django, SQL, HTML/CSS, JavaScript",
    nivel_idioma="Inglés: Nivel B1"
)

biografia = mi_perfil.crear_biografia()
print(biografia)

```
<br>
<br>
<em> "La función de un buen software es hacer que lo complejo aparente ser simple" </em><br>
<em>-- Grady Booch</em>















