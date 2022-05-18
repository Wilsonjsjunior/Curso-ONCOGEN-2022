# Curso-ONCOGEN-2022
Repositório criado para detalhar os passos do curso prático de bioinformática que será ministrado no ONCOGENE 2022.

# Minicurso: Bioinformática aplicada a medicina de proceisão

* Curso organizado para o Seminário de ocongenética do Nordeste [Oncogene](https://sis.automacaodeeventos.com.br/2022/Oncogene/sis/inscricao/index.asp)

## Sinopse

> O Sequenciamento de Nova Geração (NGS) tem possibilitado uma produção sem precedentes de dados genéticos. A análise subsequente desses dados, em busca de variantes genéticas que possam estar associadas a determinado fenótipo, é um importante passo para novas alternativas de diagnóstico e tratamento personalizado de pacientes. Este minicurso visa introduzir como é feito o tratamento dos dados de NGS advindos de DNA humano por meio de ferramentas de bioinformática, passando pelas etapas de análise de qualidade, alinhamento, chamada e anotação de variantes.

* [Link para os slides](https://docs.google.com/presentation/d/1phNV2TlAfsjnXjuIhgQECl7-0eciM_wOLi-l-Qfx1a0/edit#slide=id.g3a46271903_0_313)

## Sobre o Varsomics

![genomika-hiae](https://image-store.slidesharecdn.com/2e4dfba0-74ad-4ea6-9fe4-388de0ec294b-original.jpeg)

## Como instalar o git

```bash
sudo apt-get install git-all
```

> Para mais informações e outros sistemas operacionais, [clique aqui](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)

## Como clonar esse repositório

1. Vá para uma pasta onde queira deixar este repositório;
2. Use o comando abaixo:

```bash
git clone https://github.com/genomika/snnbcourse.git 
``` 

## Como instalar conda
* [Link ensinando como instalar](https://conda.io/docs/user-guide/install/index.html)

## Como rodar o container Docker

Faça a instalação do Docker de acordo com o seu sistema operacional:

* [Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows) (Para usar o Docker no Windows, use o [Cmder](http://cmder.net/) para emular um terminal)
* [Ubuntu](https://store.docker.com/editions/community/docker-ce-server-ubuntu)
* [Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac)

As instalações de outros sistemas operacionais podem ser encontradas [aqui](https://www.docker.com/community-edition).

Após a instalação, faça download da imagem do curso.

```
$ docker pull wildergalvao/gnmk-snnb
```

Vá para o diretório do repositório do curso, e depois crie um container com a imagem baixada, utilizando o seguinte comando:

```
$ docker container run --rm -it -v $(pwd):/curso-genomika-snnb/snnbcourse wildergalvao/gnmk-snnb
```

No final, será criado um container com todos os softwares necessários para a execução prática do curso já instalados.

## Outros cursos aqui no github, a maioria em inglês

* [In-depth NGS Data Analysis Course](https://github.com/hbctraining/In-depth-NGS-Data-Analysis-Course)
* [Applied Computational Genomics Course at UU: Spring 2018](https://github.com/quinlan-lab/applied-computational-genomics)
* [JHU EN.601.749: Computational Genomics: Applied Comparative Genomics](https://github.com/schatzlab/appliedgenomics2018)
* [NGS course by @imedina](https://github.com/ngs-course/ngs-course.github.io) - http://www.ngscourse.org/
* [Computational Genomics by Ben Lang](https://github.com/BenLangmead/comp-genomics-class)
* [Wrangling Genomics](https://github.com/datacarpentry/wrangling-genomics) - https://datacarpentry.org/wrangling-genomics/
* [I Workshop de Verão de Bioinformática pela Genomika](https://github.com/genomika/summercourse)
* [Introduction to second generation NGS data analysis](https://github.com/geocarvalho/ngs-studies/tree/master/biome-ngs)

### Mais informações:
`wilson.jsilva@einstein.br` ou `wilson.jsilva@varsomics.com`
