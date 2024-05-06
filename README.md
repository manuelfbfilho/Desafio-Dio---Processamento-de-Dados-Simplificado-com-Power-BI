<h1>
    <a href="https://www.linkedin.com/in/manuelfbfilho">
     <img align="center" width="50px" src="https://github.com/manuelfbfilho/Burcador_CEP/blob/main/Fernandes.png?raw=true"></a>
    <span> 
Desafio - Processando e Transformando Dados com PBI
</span>
</h1>

## Descrição do Desafio – Processamento de Dados Simplificado com Power BI
1. Criação de uma instância na Azure para MySQL
2.	Criar o Banco de dados com base disponível no github
3.	Integração do Power BI com MySQL no Azure 
4.	Verificar problemas na base a fim de realizar a transformação dos dados


### Diretrizes para transformação dos dados
1. Verifique os cabeçalhos e tipos de dados
2.	Modifique os valores monetários para o tipo double preciso
3.	Verifique a existência dos nulos e analise a remoção
4.	Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente
5.	Verifique se há algum departamento sem gerente
6.	Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas
7.	Verifique o número de horas dos projetos
8.	Separar colunas complexas
9.	Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção
10.	Neste processo elimine as colunas desnecessárias. 
11.	Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.
12.	Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores
13.	Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único. Isso irá auxiliar na criação do modelo estrela em um módulo futuro.
14.	Explique por que, neste caso supracitado, podemos apenas utilizar o mesclar e não o atribuir.<br>
![image](https://github.com/manuelfbfilho/Desafio-Dio---Processamento-de-Dados-Simplificado-com-Power-BI/assets/151965418/efaf747f-4f78-4115-b8fe-ac949be4cd58) ![image](https://github.com/manuelfbfilho/Desafio-Dio---Processamento-de-Dados-Simplificado-com-Power-BI/assets/151965418/d274ab99-07a1-49e4-ba27-6361c563b398)


15.	Agrupe os dados a fim de saber quantos colaboradores existem por gerente
16.	Elimine as colunas desnecessárias, que não serão usadas no relatório, de cada tabela


### Lembrar de: 
* Criar a segunda página do relatório 
* Publique o seu relatório no Power BI Service 
* Caso você tenha familiaridade fique livre para utilizar outros artifícios nos botões e outros 
* Submenta seu projeto através do link no github

 ... 




## Contatos 
[![Linkedin](https://img.shields.io/badge/Linkedin-000?style=for-the-badge&logo=linkedin&logoColor=30A3DC)](https://www.linkedin.com/in/manuelfbfilho)
<br>
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://github.com/manuelfbfilho)
