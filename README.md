# Introdução ao controle de versão com git, GitHub e RStudio

## Apresentar os principais conceitos sobre o controle de versão usando git, GitHub e RStudio

**Ministrante** <br>
Maurício Humberto Vancine

**Carga horária** <br>
3 horas

**Slides** <br>
[Slides](https://mauriciovancine.github.io/short-course-git-github-rstudio/slides/pres_short_course_git_github_rstudio.html)

---

### Informações aos participantes

**Contato** <br>
Para mais informações ou dúvidas, envie e-mail para Maurício Vancine (mauricio.vancine@gmail.com)

---

### Instruções aos participantes

**Hardware** <br>
Será necessário que todos usem seus notebooks

**Softwares** <br>
R, RStudio e git

1. Instalar a versão mais recente do [R (4.0.x)](https://www.r-project.org) e [RStudio (1.4.x)](https://www.rstudio.com)
- [Vídeo de instalação do R e do RStudio](https://youtu.be/l1bWvZMNMCM)

2. Instalar o [git (2.30)](https://git-scm.com/downloads)
- [Vídeo de instalação do git](https://youtu.be/QSfHNEiBd2k)

#### Linux (Ubuntu)

```
# r
sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys E298A3A825C0D65DFD57CBB651716619E084DAB9
gpg --keyserver keyserver.ubuntu.com --recv-key E298A3A825C0D65DFD57CBB651716619E084DAB9
gpg -a --export E298A3A825C0D65DFD57CBB651716619E084DAB9 | sudo apt-key add -
sudo add-apt-repository "deb https://cloud.r-project.org/bin/linux/ubuntu focal-cran40/"
sudo apt update
sudo apt install -y r-base r-base-core r-recommended r-base-dev

# rstudio
wget -c https://download1.rstudio.org/desktop/bionic/amd64/rstudio-1.4.1106-amd64.deb
sudo dpkg -i rstudio-1.4.1106-amd64.deb
sudo apt install -fy
rm rstudio-1.4.1106-amd64.deb

# git
sudo add-apt-repository ppa:git-core/ppa 
sudo apt update
sudo apt install -y git
```

---