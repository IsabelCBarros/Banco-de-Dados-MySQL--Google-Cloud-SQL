<div align="center"> 
  
# Python - Semana 5 - Bootcamp Análise de Dados SoulCode Academy 


 <div align="center"> 

##  Criando, populando um banco de dados e fazendo uso dos principais comandos para consulta.


 <div align="center"> 
  
![image](https://github.com/IsabelCBarros/Python---Bootcamp---Analise-de-Dados---SoulCode/assets/100105009/e3660cde-fb2d-4615-8f5f-0f7daa192e55)

## Aprendendo conceitos básicos:

## Banco de Dados Relacionais
É um conjunto de informações que organiza dados em relações predefinidas, em que os dados são armazenados em uma ou mais tabelas (ou "relações") de colunas e linhas, facilitando a visualização e a compreensão de como as diferentes estruturas de dados se relacionam. Os relacionamentos são uma conexão lógica entre diferentes tabelas, estabelecidas com base na interação entre essas tabelas.
Fonte: https://cloud.google.com/learn/what-is-a-relational-database?hl=pt-br

## SQL
O SQL é uma linguagem padrão para manipulação de registros em bancos de dados relacionais. A sigla SQL vem dos termos em inglês “Structured Query Language”, que podem ser traduzidos para o português como “Linguagem de Consulta Estruturada”. 
Fonte: https://blog.betrybe.com/sql/#1

## Modelagem
Ter um banco de dados organizado é extremamente importante para as empresas! 
Para conseguir fazer isso corretamente temos o que chamamos de modelagem de dados. Etapas:

## Entendimento do Problema: 
Ex. Se você é do setor financeiro em uma empresa você terá que saber o que é importante modelar dentro daquele sistema.

## MER (Modelo Entidade Relacionamento):
É no MER que nós iremos identificar essas entidades, atributos e relacionamentos. Ex. O relacionamento entre a entidade PROFESSOR e a entidade ALUNO, por exemplo, é que o “professor ministra aula” para o aluno.

## DER (diagrama entidade relacionamento):
Definido as nossas entidades, características e relacionamentos temos que colocá-los em um diagrama simples de ser compreendido.

Há 8 etapas para Modelagem de Dados que podem ser vistas no site: https://www.hashtagtreinamentos.com/oito-etapas-para-modelagem-de-dados-sql

## Revisão de SQL: Principais comandos

* SELECT: O comando SELECT é usado para recuperar dados de um banco de dados. Ele permite selecionar colunas específicas ou todas as colunas de uma tabela. Além disso, é possível aplicar filtros usando a cláusula WHERE.
  
* INSERT INTO: O comando INSERT INTO é usado para inserir novos registros em uma tabela.
  
* UPDATE: O comando UPDATE é usado para atualizar registros existentes em uma tabela.
  
* DELETE FROM: O comando DELETE FROM é usado para excluir registros de uma tabela.
  
* CREATE TABLE: O comando CREATE TABLE é usado para criar uma nova tabela no banco de dados, especificando as colunas e seus tipos de dados.
  
* ALTER TABLE: O comando ALTER TABLE é usado para adicionar, modificar ou excluir colunas.
  
* JOIN: O comando JOIN é usado para combinar dados de duas ou mais tabelas com base em uma coluna em comum.
  
* WHERE: Finalidade: Utilizado para filtrar registros em uma consulta com base em condições especificadas.
  
* DISTINCT: Finalidade: Remove registros duplicados da saída de uma consulta, retornando valores únicos.
  
* LIMIT: Finalidade: Restringe o número de registros retornados por uma consulta.
  
* BOOLEANOS (AND/OR/NOT): Finalidade: Utilizados para combinar condições em uma cláusula WHERE.
  
* Funções de agregação (SUM, AVG, MAX, MIN, COUNT e ROUND): Finalidade: Realiza cálculos em um conjunto de valores, retornando um único valor como resultado.
  
* GROUP BY: Finalidade: Agrupa registros com base nos valores de uma ou mais colunas, permitindo aplicar funções de agregação aos grupos resultantes.
  
* HAVING: Finalidade: Usado em conjunto com GROUP BY para filtrar grupos com base em condições agregadas.
  
* UNION: Finalidade: Combina o resultado de duas ou mais consultas em uma única saída.
  
* IN, BETWEEN, LIKE: Finalidade: Operadores para filtrar registros com base em listas, intervalos ou padrões de texto.
  
* CAST: Finalidade: Converte o tipo de dados de uma coluna para outro tipo de dados.
  
* CASE: Finalidade: Realiza uma avaliação condicional similar ao IF/ELSE, retornando diferentes valores com base em condições.
  
* VIEW: Finalidade: Uma visão é uma consulta SQL armazenada que pode ser tratada como uma tabela virtual. Ela simplifica consultas complexas e pode ser usada em outras consultas como uma tabela regular.

