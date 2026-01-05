<!-- Logo da parte de cima -->
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0077FF&height=120&section=header&text=FortunaArthur&fontColor=B2D8FF&animation=twinkling"/>

```Python
import csv

# Cabeçalhos
Cabecalhos = ["Nome", "Estudos", "Linguagens", "Ferramentas", "Experiencias", "Conhecimentos", "Contatos"]

# Dados
Nome = "Arthur Sanchez Fortuna"
Estudos = "Ciência da Computação, Fullstack, Ciência de Dados e Machine Learning, Engenharia de Software"
Linguagens = "Python, SQL, PHP, HTML, CSS, Java, JavaScript, Cobol, TypeScript"
Ferramentas = "VS Code, Jupyter Notebook, MySQL Workbench, XAMPP, DBeaver, Docker, Grafana, Node"
Experiencias = "1 Ano como Trainee, atuando como Analista de Sistemas"
Conhecimentos = "ETL, ServiceNow, BrTrix"
Contatos = "arthur.trabalho2646@gmail.com"

MeusDados = [Nome, Estudos, Linguagens, Ferramentas, Experiencias, Conhecimentos, Contatos]

# Escrever CSV
with open("Arthur_info.csv", "w", encoding='utf-8', newline='') as Arquivo:
  Escritor = csv.writer(Arquivo)
  Escritor.writerow(Cabecalhos)
  Escritor.writerow(MeusDados)

print("✅ CSV criado com sucesso: Arthur_info.csv")
```
<!-- Contadores -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=FortunaArthur&theme=react"/>

![Visitas no perfil](https://komarev.com/ghpvc/?username=FortunaArthur&label=Visitas%20no%20perfil&color=0077FF&style=flat)
![Repos Públicos](https://img.shields.io/badge/dynamic/json?url=https://api.github.com/users/FortunaArthur&query=public_repos&label=Repositórios%20Públicos&color=blue)

<!-- Jogo da Cobrinha -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/FortunaArthur/FortunaArthur/blob/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/FortunaArthur/FortunaArthur/blob/output/github-contribution-grid-snake.svg" />
  <img alt="Snake animation" src="https://github.com/FortunaArthur/FortunaArthur/blob/output/github-contribution-grid-snake.svg" />
</picture>

<!-- Roda pé -->
<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0077FF&height=120&section=footer"/>






