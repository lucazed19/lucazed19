## 👋 Hello! Welcome to my Github profile.
### My name is Lucas Sechirolli and my nickname is "lucazed19"!
[avatart](./images/octacat)


## Sobre mim 🎓
- Tenho 18 anos, moro no Brasil e curto tecnologia. 
- Atualmente estou focado mais em desenvolvimento front-end.
- Estou cursando Ciências da Computação no Centro Universitário Barão de Mauá.
- Meus Hobbies são jogar videogame e assistir animes/séries.

### Contatos 📱
<a href="https://instagram.com/lucazed_" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>

## Ferramentas e Tecnologias 🖥️
 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />
 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original-wordmark.svg" />
 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" />
 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" />
 
 ## Estou Aprendendo 🖥️
 <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" />
 
 <div>
<a href="https://github.com/lucazed19">
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucazed19&layout=compact&langs_count=7&theme=dracula"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=lucazed19&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>

![Snake animation](https://github.com/lucazed19/lucazed19/blob/output/github-contribution-grid-snake.svg)
name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: lucazed19
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

 
         
 
 
          
          
