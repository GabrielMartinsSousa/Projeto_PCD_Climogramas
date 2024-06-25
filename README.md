<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/6c7eeaea-a3c9-43d9-b247-9799c66bad2f" alt="Texto Alternativo" width="800">

Programa usado para tratar dados climáticos de um banco de dados e gerar modelos gráficos para análise

>:construction: Projeto em construção :construction:

### Índice 

- [Introdução](#Introdução)
  
- [Recursos Utilizados](#Recursos-Utilizados)
  
- [Abrir e Rodar o Projeto](#abrir-e-rodar-o-projeto)
  
- [Como Funciona](#Como-funciona)

- [Aplicações](#aplicações)

- [Acesso ao Projeto](#acesso-ao-projeto)

- [Desenvolvedores e colaboradores](#desenvolvedores-e-colaboradores)

## Introdução 


 Este é um projeto em ciência de dados para disciplina Prática em Ciência de Dados do curso de Bacharelado em Ciência e Tecnologia da [Ilum Escola de Ciência](https://ilum.cnpem.br). Devido aos recentes acontecimentos climáticos, tanto no Brasil quanto no exterior, nós, alunos da Ilum, decidimos criar um programa que permite analisar dados meteorológicos de diversas cidades do Brasil e gerar gráficos de diferentes tipos dependendo dos parâmetros analisados, como temperatura, pluviosidade, incidência de radiação solar, umidade relativa do ar e direção e intensidade do vento. A partir desses dados, é possível observar os padrões e tentar prever como o clima se comportará.

Os dados foram obtidos no site do Instituto Nacional de Metereologia, são correspondentes aos anos de 2001 até 2023 e, no último ano, apresentam dados de 567 estações metereológicas em cidades ao longo do Brasil. O download dos dados é feito no [site do INMET](https://portal.inmet.gov.br/) no formato de uma planilha do Excel. 

![Esquema Chuva de Dados](https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/54fc6137-ba47-4637-99fb-683d5ebdd118)


## Recursos Utilizados

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/c09f167c-934b-4419-96cf-4e4c3cab4c56" alt="Texto Alternativo" width="100">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/eafee038-e9ba-489b-b29d-f8f376f8fc6b" alt="Texto Alternativo" width="90">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/04fa28d7-75ce-4236-bfc7-ec0451a4ed48" alt="Texto Alternativo" width="100">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/d49d7621-add3-49af-aa70-92693cf061f8" alt="Texto Alternativo" width="164">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/025152bd-de97-420c-8a96-bf4d675bea31" alt="Texto Alternativo" width="101">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/dd5953d4-0b62-467b-85ed-9a992d6c1511" alt="Texto Alternativo" width="101">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/fad65bea-c9cf-4c61-92cc-5622b4521544" alt="Texto Alternativo" width="101">

<img src="https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas/assets/172425313/314dcd00-784b-4f40-b361-a46329aad30e" alt="Texto Alternativo" width="145">

Diversas bibliotecas foram utilizadas ao longo do código, além das citadas acima, utilizamos também a biblioteca glob, para trabalhar melhor com os dados e a biblioteca windrose, para plotar as rosas do ventos.

## Abrir e rodar o projeto

<p align="justify">

- O programa deve ser aberto em uma plataforma de compilação e rodagem de Python. 
- Além disso, é necessário baixar os dados metereológicos de todos os anos no site do INMET, o que pode ser feito na seção "Dados Metereológicos".
- Com tudo isso, o usuário deve inserir os dados necessários para a devida execução do código.
- E "Voilá", rapidamente você obtêm os gráficos desejados.

## Como funciona

<p align="justify">
Passo a Passo da Utilização do Programa:
 
- Informar qual ano quer analisar
- Informar o intervalo de tempo que quer analisar
- Informar a cidade de origem dos dados
- Informar qual tipo de modelo gráfico quer observar
  
O programa primariamente apresenta dados anuais, porém, dentro de um ano, o usuário pode definir um intervalo de tempo para delimitar os dados da maneira que achar melhor. Dependendo do ano pesquisado, algumas cidades ainda não tinham registros, portanto, não é possível analisar esses casos.
  
O usuário do Chuva de Dados seleciona a cidade da qual deseja os dados, as variáveis e o período que quer avaliar, o programa retira os dados do banco de dados e retorna ao usuário os gráficos que melhor apresentam os dados solicitados

## Aplicações

<p align="justify">
Os modelos gráficos fornecidos com o Chuva de Dados são extremamente úteis para a análise dos eventos climáticos e como se preparar caso haja uma tendência de alta ou baixa temperatura, ou até alto índice de pluviosidade e intensidade dos ventos.

## Acesso ao Projeto

O projeto Chuva de Dados está disponível no GitHub, e pode ser [baixado aqui](https://github.com/GabrielMartinsSousa/Projeto_PCD_Climogramas) a qualquer momento.

## Desenvolvedores e Colaboradores

<p align="justify">
O trabalho contou com diversos colaboradores, o principal deles foi o Professor Doutor Leandro Nascimento Lemos, que guiou e avaliou o projeto, além dele, o estagiário Duanny Silva Onório foi de grande ajuda em dúvidas e problemas na produção do código. A seguir, os perfis dos belíssimos computeiros que desenvolveram este projeto.

 [<img src="https://avatars.githubusercontent.com/u/172425251?s=400&u=ff5b960a4e2477b83fc50760e6306b118f3e95c5&v=4" width=115><br><sub>Raquel de Godoy Vianna</sub>](https://github.com/RaquelGVianna) 
 
Estudante da Ilum e Pianista

 [<img src="" width=115><br><sub>Rômulo Emanuel Rabelo Cruz</sub>](https://github.com/Romulo177)
 
 Estudante da Ilum e Jogador de Xadrez
 
 [<img src="https://avatars.githubusercontent.com/u/172425313?v=4" width=115><br><sub>Gabriel Martins Sousa</sub>](https://github.com/GabrielMartinsSousa)
 
 Estudante da Ilum e Jogador amador de Videogames

  [<img src="https://avatars.githubusercontent.com/u/38091359?v=4" width=115><br><sub>Emanuel Piveta Pozzobon</sub>](https://github.com/crovim)

 Estudante da Ilum e Calistenista

