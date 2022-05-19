# Curso-ONCOGEN-2022

Repositório criado para detalhar os passos do curso prático de bioinformática que será ministrado no ONCOGENE 2022.

# Minicurso: Bioinformática aplicada a medicina de proceisão

* Curso organizado para o Seminário de ocongenética do Nordeste [Oncogene](https://sis.automacaodeeventos.com.br/2022/Oncogene/sis/inscricao/index.asp)

## Sinopse

O Sequenciamento de Nova Geração (NGS) tem possibilitado uma produção sem precedentes de dados genéticos. A análise subsequente desses dados, em busca de variantes genéticas que possam estar associadas a determinado fenótipo, é um importante passo para novas alternativas de diagnóstico e tratamento personalizado de pacientes. Este minicurso visa introduzir como é feito o tratamento dos dados de NGS advindos de DNA humano por meio de ferramentas de bioinformática, passando pelas etapas de análise de qualidade, alinhamento, chamada e anotação de variantes.

## Sobre o Varsomics

[Varsomics]([https://image-store.slidesharecdn.com/2e4dfba0-74ad-4ea6-9fe4-388de0ec294b-original.jpeg](https://varsomics.com/?utm_term=varsomics&utm_campaign=%5BS%5D%20Institucional%20-%20BR&utm_source=adwords&utm_medium=ppc&hsa_acc=8786973005&hsa_cam=10265274196&hsa_grp=126042524043&hsa_ad=543302875654&hsa_src=g&hsa_tgt=kwd-1645495574761&hsa_kw=varsomics&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gclid=Cj0KCQjwspKUBhCvARIsAB2IYutVy_0hZtjL1yuOAXf26QN1akv4dVIJd8xpaaej0QDQ_oOOV3dOAroaAgz9EALw_wcB)

## Como instalar o git

```bash
sudo apt-get install git-all
```

> Para mais informações e outros sistemas operacionais, [clique aqui](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Instalando-o-Git)

## Como clonar esse repositório

1. Vá para uma pasta onde queira deixar este repositório;
2. Use o comando abaixo:

```bash
git clone https://github.com/Wilsonjsjunior/Curso-ONCOGEN-2022.git
```

## Como instalar conda

* [Link ensinando como instalar](https://conda.io/docs/user-guide/install/index.html)

## Como rodar o container Docker

Faça a instalação do Docker de acordo com o seu sistema operacional:

* [Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows) (Para usar o Docker no Windows, use o [Cmder](http://cmder.net/) para emular um terminal)
* [Ubuntu](https://store.docker.com/editions/community/docker-ce-server-ubuntu)
* [Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac)

As instalações de outros sistemas operacionais podem ser encontradas [aqui](https://www.docker.com/community-edition).

Após a instalação, faça a build da imagem no seu computador:

```bash
dodocker build -t oncogene -f dockerfile .
```

Vá para o diretório do repositório do curso, e depois crie um container com a imagem baixada, utilizando o seguinte comando:

```bash
docker container run --rm -it -v $(pwd):/curso-genomika-snnb/snnbcourse wildergalvao/gnmk-snnb
```

No final, será criado um container com todos os softwares necessários para a execução prática do curso já instalados.

### Mais informações:

`wilson.jsilva@einstein.br` ou `wilson.jsilva@varsomics.com`
