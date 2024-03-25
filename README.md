<h1>Bootcamp Coding The Future Squadio Python Data Analytics</h1>

<section id="topo">           
<img src="https://hermes.dio.me/tracks/0136518c-68d6-4198-bdbe-6d982c3a1261.png" alt="Logo Bootcamp" width="120"> 
<img src="https://hermes.dio.me/courses/badge/99f0adda-dc01-46ec-bd29-61c3deceb76c.png" alt="Logo Bootcamp" width="100">
<img src="https://hermes.dio.me/courses/badge/92b14ead-e8b4-4eca-ab08-6800c8242469.png" alt="Logo Bootcamp" width="100">
<img src="https://hermes.dio.me/courses/badge/aae7029a-856f-40a1-8be2-effed1ff5a83.png" alt="Logo Bootcamp" width="100">
 
</div>

<h1 align="center"> Projeto Processamento de Dados Simplificado com Power-BI </h1>

 ## Passos do Desafio
- Criação de uma instância na Azure para MySQL
Crie uma instância na plataforma Azure para MySQL, onde os dados serão armazenados e posteriormente acessados pelo Power BI.
- Criar o Banco de Dados com Base Disponível no GitHub
Utilize a base de dados disponível no GitHub como ponto de partida para este desafio. Importe ou crie o banco de dados no MySQL na Azure de acordo com as especificações fornecidas.
- Integração do Power BI com MySQL na Azure
Configure a integração entre o Power BI e o MySQL na Azure para permitir a conexão e a extração dos dados para análise.
- Verificar Problemas na Base para Realizar a Transformação dos Dados
Antes de iniciar as transformações, verifique e identifique problemas na base de dados que possam afetar a análise posterior. Esses problemas podem incluir inconsistências nos tipos de dados, valores nulos ou outras irregularidades.
![image](https://github.com/Elbiabuglio/Projeto-Processamento-de-Dados-Simplificado-com-Power-BI/assets/101484328/d2e9dd73-c5ec-42db-9b69-9cf47811aa42)
![image](https://github.com/Elbiabuglio/Projeto-Processamento-de-Dados-Simplificado-com-Power-BI/assets/101484328/eb26caec-711f-4ad8-adbd-ce34c02b1942)
## Diretrizes para Transformação dos Dados
- Verificar os Cabeçalhos e Tipos de Dados
- Certifique-se de que os cabeçalhos das colunas estejam corretos e os tipos de dados estejam apropriados para cada campo.
## Modificar os Valores Monetários para o Tipo Double Preciso
- Transforme os valores monetários para o tipo de dados double preciso para garantir maior precisão nos cálculos.
## Verificar a Existência dos Nulos e Analisar a Remoção
- Analise a presença de valores nulos e avalie a necessidade de removê-los ou substituí-los por valores adequados.
## Identificar Employees sem Gerentes
- Verifique se há colaboradores sem gerentes, especialmente aqueles com valores nulos em "Super_ssn".
## Identificar Departamentos sem Gerentes
- Verifique se existem departamentos sem gerentes atribuídos.
## Preencher as Lacunas nos Departamentos sem Gerentes
- Suponha que você possui os dados necessários para preencher as lacunas nos departamentos sem gerentes.
## Verificar o Número de Horas dos Projetos
- Analise e verifique o número de horas registradas para cada projeto.
## Separar Colunas Complexas
- Se necessário, separe colunas complexas em colunas individuais para facilitar a análise.
## Mesclar Consultas Employee e Department
- Crie uma tabela que associe os colaboradores aos seus respectivos departamentos, utilizando a mescla de consultas ou tabelas. A mescla deve ser baseada na tabela "employee".
## Eliminar Colunas Desnecessárias
- Remova quaisquer colunas desnecessárias das tabelas resultantes da transformação dos dados.
## Realizar a Junção dos Colaboradores e seus Respectivos Gerentes
- Utilize consultas SQL ou a mescla de tabelas com Power BI para realizar a junção dos colaboradores com os seus respectivos gerentes. Se utilizar SQL, especifique a query no README.
## Mesclar as Colunas de Nome e Sobrenome
- Combine as colunas de nome e sobrenome em uma única coluna para facilitar a análise dos nomes dos colaboradores.
## Mesclar os Nomes de Departamentos e Localização
- Combine os nomes de departamentos e suas localizações em uma única coluna para criar uma combinação única para cada departamento, facilitando a criação de um modelo estrela em módulos futuros.
## Explicar o Uso de Mesclar ao Invés de Atribuir
- A mescla é preferível ao atribuir porque queremos combinar informações de funcionários e departamentos com base em uma chave comum, o código do departamento. Ao mesclar as tabelas, obtemos uma única tabela que contém todas as informações relevantes, facilitando análises detalhadas, como a contagem de funcionários por departamento, e simplificando a criação de visualizações significativas no Power BI. Isso elimina a necessidade de operações adicionais de atribuição ou lookup, tornando o processo mais eficiente e fácil de manter.
## Agrupar os Dados por Gerente
- Agrupe os dados para determinar quantos colaboradores existem por gerente.
## Eliminar Colunas Desnecessárias
- Remova quaisquer colunas desnecessárias que não serão utilizadas no relatório final, visando manter a simplicidade e eficiência do modelo de dados.
 
![Captura de Tela (8)](https://github.com/Elbiabuglio/Projeto-Processamento-de-Dados-Simplificado-com-Power-BI/assets/101484328/4912eacc-cfb9-4b65-91bb-9811f9e74f6e)
![Captura de Tela (6)](https://github.com/Elbiabuglio/Projeto-Processamento-de-Dados-Simplificado-com-Power-BI/assets/101484328/6422aedc-6d7e-4eb0-a3e5-134a166c65a0)




