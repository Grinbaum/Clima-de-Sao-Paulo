# Clima de São Paulo
Projeto de exercício acadêmico, de extração de dados da previsão de temperatura de São Paulo no site Climatempo

## Objetivo

Este projeto foi desenvolvido para o curso Master em Jornalismo de Dados, Automação e Data Storytelling, do Insper. Seu objetivo é exercitar técnicas ensinadas em duas disciplinas: Pensamento Computacional, do professor Álvaro Fernandes de Abreu Justen, e Transparência, Reprodutibilidade e Uso Ético de Dados, das professoras  Natália Passos Mazotte Cortez e  Carla Piazzon Ramos Vieira.

A disciplina Pensamento Computacional é voltada para o aprendizado da linguagem Python e de práticas de programação. No projeto, pretende-se exercitar essas técnicas, por meio do desenvolvimento de códigos para a raspagem dos dados de um site e para baixar e manipular os dados em um computador.

Já a disciplina Transparência, Reprodutibilidade e Uso Ético de Dados discute a importância do rigor metodológico, da documentação precisa e da divulgação dos processos de programação. O objetivo dessas práticas é facilitar a checagem das informações e democratizar o acesso aos dados. A parte do projeto voltada para essa disciplina prevê a documentação no Github, de maneira clara e detalhada, dos códigos usados para o exercício de raspagem de dados. 

## Conteúdo

Na prática, o projeto Clima de São Paulo consiste em um exercício de extração de informações do site Climatempo. Seu objetivo é obter as previsões diárias de temperaturas mínima e máxima na cidade de São Paulo e a organização dessas informações em uma tabela no formato CSV. Ao final, prevê-se a elaboração de um gráfico com a evolução das previsões ao longo de um mês.

Trata-se de um projeto em construção. Por enquanto, o resultado da pesquisa diária está sendo direcionado a tabelas separadas em CSV. O objetivo final é reunir todos os dados em uma só tabela. Também ainda não foi preparado o gráfico com a evolução das previsões de temperatura.

Neste repositório aparecem dois códigos. O primeiro deles ('raspaclima.ipynb') é para extrair dados do Climatempo e criar a tabela de dados em CSV. O segundo ('Raspaclima3.ipynb') faz a mesma coisa, mas incorpora uma função para facilitar o trabalho.

## Como foi feito

O Climatempo é uma empresa especializada em metereologia. Em seu site, a empresa divulga previsões diárias do tempo em cidades brasileiras e de outros países.

O projeto busca retirar todos os dias as previsões de temperatura mínima e temperatura máxima para a cidade de São Paulo. Para isso, recorre à página do site Climatempo voltada a São Paulo: https://www.climatempo.com.br/previsao-do-tempo/cidade/558/saopaulo-sp

Os dados são extraídos por meio de códigos em Python e armazenados em tabelas no formato CSV no computador. O código 'raspaclima.ipynb'extrai os dados com a execução passo a passo. Já o código 'Raspaclima3.ipynb' prevê a criação de uma função para a extração dos dados de maneira direta.

Uma segunda parte dos códigos formata os dados em uma tabela na linguagem pandas. Em seguida, a tabela é convertida para um arquivo em formato CSV.A tabela é baixada em um arquivo no computador.

Os códigos utilizam as seguintes bibliotecas da linguagem Python: Request, BeautifulSoup, Datetime, Pandas e CSV. Como se trata de um exercício acadêmico, ao lado de cada linha dos códigos anexados neste repositório há uma explicação para o que foi feito.  

## Contribuição

Como o objetivo deste projeto é acadêmico, o exercício de técnicas e das melhores práticas de programação, ele não está aberto a contribuições.

