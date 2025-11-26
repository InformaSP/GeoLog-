|# GeoLog 
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/3f0e230b-87c4-41b9-8057-afddec5ab5a9" />


# Aprendizado por Projeto Integrado (API) 

Nós, alunos do 2° semestre do curso de Logística da Fatec, desenvolvemos este projeto com o propósito acadêmico de complementar e aprimorar nossa capacidade analítica e logística, envolvendo a prática da interdisciplinaridade. O Projeto é baseado na metodologia ágil SCRUM, buscando desenvolver a proatividade, autonomia, colaboração e entrega de resultados dos estudantes envolvidos.

# Índice

* [Projeto](#projeto-template)
* [Equipe](#equipe)
* [Objetivo do Projeto](#objetivo-do-projeto)
* [Cronograma das Sprints](#Cronograma-das-Sprints)
* [Backlog do produto](#Backlog-do-produto)


# Projeto (API) 
No segundo semestre do curso de Logística, fomos desafiados a desenvolver uma ferramenta com tratamento de dados do IBAMA que permita uma análise detalhada e dinâmica sobre os indicadores  de movimentação de cargas perigosas, no processo incluido a limpeza e a  preparação da base de 2021 a 2025 do Fluxo de Cargas Especiais e Perigosas de Empresas com Registro no RAPP, a Análise estatística de acidentes viários com veículos pesados e avaliação de proximidade dos acidentes com pontos de
parada de descanso. 


# Equipe
| Função       |Nome             | Linkedin     |
|--------------|-----------------|--------------|
|Team Member | Camila Martins  |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/camila-martins-515405219/)
|Team Member | Manoela Nobre  |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/manoela-batista-nobre-800206271/)
|Team Member | Vitória Beatriz |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/vit%C3%B3ria-beatriz-mariano-6281a8292?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
|Product Owner  | Gabriele Fujita |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gabrielle-fujita-4151b0198?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
|Scrum Master   | Ana R. Araújo   |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ana-ara%C3%BAjo-tom%C3%A9-754936215?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
|Team Member   | Kelvin Sampaio  |[![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/kelvin-sampaio-139a462b4?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)


# Objetivo do Projeto
O projeto tem como objetivo desenvolver uma ferramenta para análise de indicadores das movimentações de cargas, apresentando métricas por estado e nacionalmente visando:
* Analisar o fluxo de cargas especiais e perigosas no Brasil (por estado e nacionalmente).
* Identificar padrões logísticos, como principais cargas, modais de transporte, origens e destinos.
* Acompanhar a evolução ao longo do tempo (2013 a 2023).
* Relacionar acidentes viários com veículos pesados e verificar a proximidade com pontos de parada de descanso.
* Apoiar a tomada de decisão, estudos acadêmicos e possíveis políticas públicas voltadas à segurança e eficiência no transporte de cargas perigosas.


## Tecnologias Utilizadas

* Google Colab
* Power BI
* Mysql
* Trello
* Git Hub

  
# Product Backlog 

 Rank | Prioridade | User Story                                                                             | Estimativa  | Sprint     |
|------|-----------|----------------------------------------------------------------------------------------|-------------|------------|
| 1    | alta     | Como Tomador de decisões quero acesso a dados limpos e tratados em python, com informações filtradas em modal rodoviário para melhor análise das causas| 3  | 1  |
| 2    | alta     | Como Tomador de decisões quero acesso a um dashboard que contenha o Fluxo de Cargas Especiais e Perigosas do período de 2021 a 2025 de empresas que possuem registro RAPP ativo| 3  | 1  | 
| 3    | alta     |  Como Tomador de decisões logísticas quero um ranking com as cinco regiões em que mais ocorrem acidentes envolvendo cargas pesadas| 2  | 1  | 
| 4    | média   | Como Tomador de decisões quero acesso ao top 5 municípios que mais movimentaram cargas perigosas e poluentes por frota| 3  | 1  | 
| 5    | baixa  | Como Tomador de decisões quero acesso relação das 5 empresas que mais poluiram e a situação do cadastro no RAPP| 2  | 2
| 6    | alta  | Como Tomador de decisões logísticas, quero a relação dos principais modais utilizados para a movimentação de cargas perigosas| 2  | 2  |
| 7    | alta  | Como Tomador de decisões, quero a relação das cinco principais origens e destinos da movimentação de cargas perigosas, para tomada de decisões futuras e ações de prevenção e otimização de fiscalizações| 2   | 2   |
| 8    | alta   | Como Tomador de decisões, quero a relação dos pontos de descanso para motoristas de caminhões de carga perigosa em um raio de 100km das regiões em que mais ocorrem acidentes envolvendo cargas perigosas| 3   | 4   |
| 9   | alta  | Como Tomador de decisões logísticas, gostaria de ter acesso a um relatório técnico detalhando boas práticas dos 3 estados que menos causaram acidentes de transporte de cargas perigosas e quais os desafios enfrentados| 6  | 3  |
| 10  | média | Como Tomador de decisões, quero ter acesso a evolução da frota de veículos dos 5 municípios que mais transportaram cargas perigosas e poluentes durante o período| 4  | 3  |

# Desenvolvimento de dashboard no Power BI, apresentando:
Principais cargas movimentadas;
modais utilizados;
origens e destinos;
evolução ao longo do tempo;
empresas envolvidas;
acidentes viários com veículos pesados e sua proximidade com pontos de descanso.
Análises e visualizações em mapas e gráficos de tendência, com possibilidade de segmentar por estado e nível nacional.
Documentação técnica com scripts em Python e boas práticas.

Entrega final:
Dashboard funcional, limpo e intuitivo.
Relatório técnico com análises e recomendações.
Material que possa apoiar estudos acadêmicos e formulação de políticas públicas.


 # Registro das Sprints
 
 Sprint | Previsão | Status | Histórico |
|------|--------|------|--------|
|Kick Off | 03/09/2025 | concluído|  | 
| 01 | 01/10/2025| concluído |  | 
| 02 | 29/10/2025| em processo |  | 
| 03 | 19/11/2025 | a fazer |  | 
| Feira de Soluções | 04/12/2025 | a fazer |  | 



<p align="center">
 <img src="https://img.shields.io/badge/STATUS-EM_PROGRESSO-yellow"/>
</p>
  










