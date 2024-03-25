# Projeto-Processamento-de-Dados-Simplificado-com-Power-BI

 ## Passos do Desafio
- Criação de uma instância na Azure para MySQL
Crie uma instância na plataforma Azure para MySQL, onde os dados serão armazenados e posteriormente acessados pelo Power BI.

- Criar o Banco de Dados com Base Disponível no GitHub
Utilize a base de dados disponível no GitHub como ponto de partida para este desafio. Importe ou crie o banco de dados no MySQL na Azure de acordo com as especificações fornecidas.

- Integração do Power BI com MySQL na Azure
Configure a integração entre o Power BI e o MySQL na Azure para permitir a conexão e a extração dos dados para análise.

- Verificar Problemas na Base para Realizar a Transformação dos Dados
Antes de iniciar as transformações, verifique e identifique problemas na base de dados que possam afetar a análise posterior. Esses problemas podem incluir inconsistências nos tipos de dados, valores nulos ou outras irregularidades.
![image](https://github.com/Elbiabuglio/Projeto-Processamento-de-Dados-Simplificado-com-Power-BI/assets/101484328/4918c26f-2ce1-4a7a-b2b3-45d473338a83)


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
- Explique por que a mescla é preferível ao atribuir neste caso específico.

## Agrupar os Dados por Gerente
- Agrupe os dados para determinar quantos colaboradores existem por gerente.

## Eliminar Colunas Desnecessárias
- Remova quaisquer colunas desnecessárias que não serão utilizadas no relatório final, visando manter a simplicidade e eficiência do modelo de dados.
