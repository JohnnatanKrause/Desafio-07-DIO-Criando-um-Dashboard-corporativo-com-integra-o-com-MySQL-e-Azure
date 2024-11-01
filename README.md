# Desafio 07: Processamento de Dados com Power BI e MySQL na Azure

👋 Olá, eu sou Johnnatan Krause! Este é o meu projeto para o **Desafio 07** do módulo de Power BI no bootcamp de **Engenharia de Dados com Python**.

## Descrição do Desafio

Neste desafio, o objetivo foi aplicar as etapas de coleta, obtenção e transformação de dados utilizando Power BI e MySQL na Azure. Segui os passos definidos nos vídeos e realizei as transformações necessárias para preparar os dados para análise.

### Objetivos

As etapas do desafio incluem:

1. **Criação de uma Instância na Azure para MySQL**: Configurei um banco de dados MySQL na Azure para armazenar os dados.
2. **Criação do Banco de Dados**: Utilizei o banco de dados disponível no GitHub para alimentar a instância.
3. **Integração do Power BI com MySQL na Azure**: Conectei o Power BI à instância do MySQL para acessar os dados.
4. **Verificação e Transformação dos Dados**: Realizei diversas verificações e transformações nos dados para garantir sua integridade e adequação à análise.

### Diretrizes para Transformação dos Dados

1. **Verificação de Cabeçalhos e Tipos de Dados**: Confirmei se todos os cabeçalhos estavam corretos e se os tipos de dados estavam adequados.
2. **Modificação de Valores Monetários**: Converti os valores monetários para o tipo `double` preciso.
3. **Análise de Valores Nulos**: Identifiquei a presença de nulos e analisei a necessidade de remoção.
4. **Gerentes Sem Colaboradores**: Verifiquei se havia colaboradores sem gerente e analisei os dados.
5. **Departamentos Sem Gerente**: Verifiquei se havia departamentos sem gerentes e preenchi as lacunas conforme necessário.
6. **Verificação de Horas dos Projetos**: Conferi a quantidade de horas registradas nos projetos.
7. **Separação de Colunas Complexas**: Realizei a separação de colunas que continham informações complexas.
8. **Mesclagem de Consultas**: Combinei as tabelas de `employee` e `department` para criar uma tabela `employee` com os nomes dos departamentos associados.
   - *Atenção*: Este processo influencia o tipo de junção utilizada.
9. **Eliminação de Colunas Desnecessárias**: Removi colunas que não seriam usadas no relatório.
10. **Junção de Colaboradores e Gerentes**: Realizei a junção para associar colaboradores a seus gerentes, utilizando SQL ou mesclagem de tabelas no Power BI. (Especificar a query utilizada se aplicável.)
11. **Mesclagem de Nome e Sobrenome**: Combinei as colunas de nome e sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores.
12. **Mesclagem de Nomes de Departamentos e Localização**: Isso garantiu que cada combinação departamento-local fosse única, facilitando a criação do modelo estrela em um módulo futuro.
   - *Justificativa*: Neste caso, utilizamos mesclar em vez de atribuir, pois a combinação de informações é mais adequada para o modelo de dados.
13. **Agrupamento de Dados**: Agrupei os dados para determinar quantos colaboradores existem por gerente.
14. **Eliminação de Colunas Desnecessárias**: Revisei e eliminei colunas desnecessárias de cada tabela que não seriam utilizadas nos relatórios.

### Visualização do Modelo

Abaixo está uma imagem do modelo final criado durante o projeto:

![Modelo Final](link-para-a-imagem-do-modelo)

## Links para Dados Utilizados

- **Dados Utilizados**: [Banco de Dados no GitHub](link-para-o-banco-de-dados)

## Dicas e Recursos para Aprofundamento

- **Cursos e Tutoriais**: Explore plataformas como DIO, Coursera, Udemy e YouTube para cursos de Power BI e MySQL.
- **Comunidades**: Participe de grupos no LinkedIn e fóruns como o Power BI Community para trocar experiências.
- **Documentação Oficial**: Consulte a [documentação do MySQL](https://dev.mysql.com/doc/) e a [documentação do Power BI](https://docs.microsoft.com/pt-br/power-bi/) para aprofundar seu conhecimento.

## Conclusão

Este desafio foi uma excelente oportunidade para aplicar conhecimentos de coleta e transformação de dados utilizando Power BI e MySQL na Azure. Estou animado para aplicar essas habilidades em projetos futuros!

## Conecte-se comigo

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/johnnatankrause/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JohnnatanKrause)
[![DIO](https://img.shields.io/badge/DIO-ff3e00?style=for-the-badge&logo=dio&logoColor=white)](https://www.dio.me/users/johnnatankrause)

## Habilidades

![Power BI](https://img.shields.io/badge/Power%20BI-F2C94C?style=for-the-badge&logo=powerbi&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

JK
