# Mapa de Cuidados de São Vicente

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

---

Este projeto foi desenvolvido no contexto da disciplina **ACH3778 - Governo Aberto** da EACH-USP, em parceria com o projeto **Coop Clima** e a **Prefeitura de São Vicente**.

A iniciativa tem como objetivo central investigar e enfrentar a problemática das **áreas contaminadas e da vulnerabilidade informacional** que persiste no município de São Vicente, propondo soluções que promovam a democratização do acesso à informação ambiental e o fortalecimento da transparência pública.

[🎬 Veja o vídeo Apresentação do Projeto](docs/apresentacao-projeto-integrador.mp4)

[📄 Veja o Relatório Final](docs/relatorio-final.pdf)

---

## Objetivos do Projeto

O projeto orienta-se pelos seguintes objetivos específicos:

- Democratizar o acesso a informações sobre áreas contaminadas no município, tornando-as compreensíveis para a população em geral;
- Traduzir dados técnicos, originalmente restritos a relatórios e sistemas especializados, em linguagem acessível e visualmente organizada;
- Fortalecer a transparência ativa e o direito à informação, em conformidade com a Lei de Acesso à Informação (Lei nº 12.527/2011);
- Promover justiça climática por meio do empoderamento informacional das comunidades expostas a riscos ambientais.

---

## Solução Proposta

A solução desenvolvida estrutura-se em quatro componentes interdependentes, que em conjunto oferecem uma resposta integrada ao problema da invisibilidade das áreas contaminadas em São Vicente.

### 1. Protótipo no Figma

O protótipo navegável da interface do portal foi desenvolvido no Figma e contempla três versões responsivas (desktop, tablet e celular). Trata-se de um website que torna as informações sobre áreas contaminadas mais acessíveis para os moradores de São Vicente, organizando os dados em linguagem simples e oferecendo uma experiência adaptada a diferentes dispositivos.

🔗 [Acesse o protótipo no Figma](https://www.figma.com/site/vc4NAG7X4egyXkwF9w6Shu/Mapa-de-cuidados-de-S%C3%A3o-Vicente?node-id=0-1&t=d9xnLGD2rMTC7m4U-1) 

[Baixar PDF do protótipo](docs/prototipo-figma.pdf)

### 2. Mapa Interativo

O mapa integra diferentes camadas de informação geoespacial, permitindo a identificação e análise de áreas contaminadas em relação ao território municipal, aos bairros e às unidades públicas. Foi desenvolvido em Python com as bibliotecas Folium e Pandas.

**📁 Localização:** `/mapa-interativo/`

### 3. Microsserviço de Consulta

API RESTful desenvolvida em **Java com Spring Boot** para consulta de áreas contaminadas próximas a uma localização informada pelo usuário. O response retorna informações detalhadas sobre as áreas contaminadas, grupo de contaminantes, medidas de intervenção e medidas de precaução.

**📁 Localização:** `/microsservico-api/`