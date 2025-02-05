<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Profiles README DIO</span>
</h1>

## Sobre o Projeto
Página desenvolvida para fins didáticos para o curso **Contribuindo em um Projeto Open Source no GitHub** da [Digital Innovation One](https://www.dio.me/). Lembre-se de que Markdown é mais voltado para a documentação e apresentação de texto formatado, enquanto a remoção de bugs normalmente envolve a compreensão detalhada do código e o uso de ferramentas de desenvolvimento adequadas à linguagem de programação específica.

[![Preview](https://img.shields.io/badge/Preview-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://digitalinnovationone.github.io/dio-lab-open-source/)

```
docs/
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── scripts.js
├── favicon.ico
├── index.html
└── README.md
```
### Instructions (EN/US)
1. **Fork** this repository;
2. Clone locally: `git clone https://github.com/YOUR_USERNAME/dio-lab-open-source.git`;
3. Add the upstream remote to keep your local repository updated. For instance: `git remote add upstream https://github.com/digitalinnovationone/dio-lab-open-source.git`;
    > Use the command `git pull upstream main` to download and merge the changes in your local repository based on the `main` branch of this original repository from which you forked, or `git fetch upstream main` to download without merging. Learn more at: [Getting Started with Git and GitHub](https://github.com/digitalinnovationone/dio-lab-open-source/blob/main/utils/git/ROADMAP_GITHUB.md).
4. Create/Reference a new **branch** and name it `feat/community/YOUR_USERNAME`: `git checkout -b feat/community/YOUR_USERNAME`;
    > Example: `git checkout -b feat/community/rafaeldscordeiro`
5. Inside the [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community) folder, create a Markdown file (extension `.md`) and name it after your GitHub username;
    > Example: `rafaeldscordeiro.md` <br>
6. Develop your profile: For that, you can see examples in the [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community) folder and add some of the utilities available in the [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils) folder;
    > **Note:** Use the other examples as inspiration, not as a copy.
7. Add your changes to the "staging area" with the command `git add community/YOUR_USERNAME.md`;
8. Create a commit and add a message indicating the addition of your profile `git commit -m"feat: add YOUR_USERNAME profile"`;
9. Push the changes to your remote repository `git push origin feat/community/YOUR_USERNAME`;
10. Create a **Pull Request**.
    
## Tecnologias
![HTML](https://img.shields.io/badge/HTML-000?style=for-the-badge&logo=html5&logoColor=30A3DC)
![CSS](https://img.shields.io/badge/CSS-000?style=for-the-badge&logo=css3&logoColor=E94D5F)
![JavaScript](https://img.shields.io/badge/JavaScript-000?style=for-the-badge&logo=javascript&logoColor=30A3DC)
