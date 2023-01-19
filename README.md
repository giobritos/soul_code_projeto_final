# Mindful Data Consultoria
**Projeto final do curso de Engenharia de dados da SoulCode Academy**

 - **Autores:** Anderson Calasans, Giovana de Brito, Suzana Gomes, Wilbert Silva
 - **Data de entrega:** January 17, 2023
 - **Resumo:** Projeto final  do curso de engenharia de dados da SoulCode Academy, com relevância na área de crimes (segurança pública), que mostra um estudo comparativo entre as cidades de São Paulo (Brasil) e New York (United States of America) quanto ao número de casos de crimes envolvendo homicídios e os dados envolvendo este tipo de ocorrência.
 - **Status:** Finalizado
 - **Tema:** Crimes (Segurança Pública)
 - **Type:** Projeto Final - Soul Code
 - **Área de estudo:** ETL, Engenharia de dados, GCP, MongoDB, MySQL, Python, SQL

## **🚀 A Mindful Data - A Empresa:**

A **Mindful Data,** empresa de consultoria da área de engenharia de dados, fundada por nós, alunos recém formados do curso de **Engenharia de Dados** da **Soul Code Academy,** tem a proposta de atender à demanda de empresas no que se trata de:

- Data Migration;
- Processos de ETL;
- Produção de insights e dashboards para apoiar decisões de negócios;

Nosso **squad** é composto por:

<div align="center">
  <img height="160em" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/ef78bf14-e393-460d-93b0-377dfc5a18c9/Design_sem_nome_%281%29.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230119%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230119T150411Z&X-Amz-Expires=86400&X-Amz-Signature=597c110a681156100510b68dfffa90060bed385587f1018f1e83f78249c000e3&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22Design%2520sem%2520nome%2520%281%29.png%22&x-id=GetObject"/>
  <img height="160em" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/e3118646-ce44-4d71-9d28-9585359c9da2/3.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230119%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230119T150405Z&X-Amz-Expires=86400&X-Amz-Signature=881af96c016ae12ec050b77df9db5d9f3b2f195e2608279c7cdb2985f70ad55d&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%223.png%22&x-id=GetObject"/>
  <img height="160em" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/8c39b4c0-2e0b-4e8d-93c8-3d306887edc3/2.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230119%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230119T150408Z&X-Amz-Expires=86400&X-Amz-Signature=1cf62d48aca6e48fb54ca3816d73ebd57f57fcd752cd2751fe9841cf8263ce56&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%222.png%22&x-id=GetObject"/>
  <img height="160em" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/72559785-117d-443a-a1f8-aa66b4c116cb/4.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230119%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230119T150413Z&X-Amz-Expires=86400&X-Amz-Signature=1cbfb8c5bd95da012d9f399ab27247604b50e8962c60579856ef863321d79e51&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%224.png%22&x-id=GetObject"/>
</div>

## ⭐ **Diretrizes:**

Nosso projeto seguiu as diretrizes determinada pelos professores do curso de engenharia de dados da SoulCode Academy e fora orientado pelo professor **Igor Gondim.** 

Os requisitos estão descritos logo abaixo:

[Requisitos do projeto](https://www.notion.so/Requisitos-do-projeto-7d9f86f72b5943e88e9c6c0ce9970a88)

## **O Projeto**

📌 **Definição dos objetivos:**

A partir do tema, passamos a etapa de definição dos objetivos e criação de insights preliminares para atender às expectativas das diretrizes passadas pelo proposto do projeto.

Essa etapa está contida aqui:

[**Objetivos e organização das ideias gerais**](https://www.notion.so/Objetivos-e-organiza-o-das-ideias-gerais-c971c8ee5b464d53a76c2474b5f3a1ac)

📊 **Tema escolhido com objetivo geral**:

> Estudo dos casos de crimes envolvendo mortes entre as cidades de **Nova York** e **São Paulo**
> 

📑 **Objetivos específicos:**

- Traçar o perfil das vítimas
- Mapear quais locais mais violentos
- Evolução da quantidade de crimes de acordo com o período

📈**Insights a serem resolvidos:**

1. Qual o total de ocorrências das duas cidades?
2. Ranking dos tipos de crime campeãs em ocorrências
3. Qual o período do dia com maior número de ocorrências?
4. Laço temporal dos crimes por ano e mês
5. Número de ocorrências por cor da pele e sexo
6. Quais as regiões (bairros ou distritos) mais perigosos?
</aside>

## **O Processo de ETL**

### 📌 **Workflow**

Todo nosso processo está descrito no modelo abaixo, passando por todos os tópicos solicitados nas diretrizes do projeto.

<div align="center">
  <img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/c588b1f8-1273-4620-8369-9a0a0831b3cc/WhatsApp_Image_2023-01-16_at_17.01.02.jpeg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20230119%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20230119T150315Z&X-Amz-Expires=86400&X-Amz-Signature=7457d97a24eb81e0af53f25a242e4babc12071e7b6e326b68cfb91dd2d80df13&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22WhatsApp%2520Image%25202023-01-16%2520at%252017.01.02.jpeg%22&x-id=GetObject"/>
</div>

### 📄**Definição das bases de dados**

Com os objetivos traçados, começamos a busca das bases de dados que utilizaremos. Nos dividimos na busca e encontramos dados oficiais de ambas as cidades disponíveis publicamente. 

Para melhorar o entendimento, a partir daqui trataremos ambas as cidades de forma paralela para facilitar a construção do raciocínio.

**São Paulo - fonte de dados:**

Os dados foram tirados do Portal transparência do Governo do Estado de São Paulo e filtrado apenas os crimes com homicídios para a cidade de São Paulo, dos anos de 2018 a 2021.

[Segurança Pública - Transparência](http://www.ssp.sp.gov.br/transparenciassp/Consulta.aspx)

**Nova York - fonte de dados:**

Os dados escolhidos estão disponíveis no site **NYC Open Data**, administrado pelos órgão públicos da cidade de **Nova York** (**USA)**, onde filtramos as ocorrências que tiveram homicídios entre os anos de 2018 a 2021.

[NYPD Complaint Data Historic | NYC Open Data](https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i)

### **Tratamentos dos dados**

Abaixo estão descritos todo o passo a passo desde a extração, até a união dos datasets de SP e NY já tratados.

**DataSet Original SP:** 
[Google Colaboratory](https://github.com/giobritos/soul_code_projeto_final/blob/d95442856ba9c7cc6da5e01db94d6c0e26276485/Import_Originais_SP.ipynb)

**DataSet Tratado SP:**
[Google Colaboratory](https://github.com/giobritos/soul_code_projeto_final/blob/d95442856ba9c7cc6da5e01db94d6c0e26276485/Tratamento_SP_Pandas.ipynb)

**DataSet Original NY:** 
[Google Colaboratory](https://github.com/giobritos/soul_code_projeto_final/blob/d95442856ba9c7cc6da5e01db94d6c0e26276485/Import_Originais_NY.ipynb)

**DataSet Tratado NY:**
[Google Colaboratory](https://github.com/giobritos/soul_code_projeto_final/blob/d95442856ba9c7cc6da5e01db94d6c0e26276485/Tratamento_NY_PySpark.ipynb)

**Data Frame juntando os dados de SP e NY:**
[Google Colaboratory](https://github.com/giobritos/soul_code_projeto_final/blob/d95442856ba9c7cc6da5e01db94d6c0e26276485/Uniao_Dados_SP_NY.ipynb)

**Envio do DataSet tratado ao BigQuery via Apache Beam:**
[Google Colaboratory](https://github.com/giobritos/soul_code_projeto_final/blob/d95442856ba9c7cc6da5e01db94d6c0e26276485/Custom_Template_GCS_para_BigQuery.ipynb)


## 📈 **Data Visualization**

### **BigQuery**
Após realizar todos os tratamentos necessários e salvar os dados nos Data Lakes (**Cloud Storage** e **MongoDB**), puxamos os dados para o BigQuery, onde fizemos os últimos ajustes e algumas queries para constatar se nosso dados atendiam ao nosso objetivo antes do envio ao Looker Studio.

### **Dashboard Looker Studio**

O DashBoard interativo foi criado com o Looker Studio e está disponível no link abaixo:
[Dashboard-Projeto Final](https://datastudio.google.com/reporting/2ecaecd3-dde9-4171-8a27-c5c589a6daed)

## **Apresentação**

🎞️ **Apresentação Grupo 1 - Crimes:**
No Link abaixo está nossa apresentação de slides, neste documento traremos mais detalhes sobre todo o processo.

[Apresentacao-Projeto Final](https://github.com/giobritos/soul_code_projeto_final/blob/d95442856ba9c7cc6da5e01db94d6c0e26276485/Grupo%201-%20Apresentacao-Projeto%20Final.pdf)
