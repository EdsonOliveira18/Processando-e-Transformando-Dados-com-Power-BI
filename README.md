# Desafio de Projeto - Processamento de Dados Simplificado com Power BI

Este repositório contém o passo a passo para o desafio de projeto do módulo 3, que envolve o processamento de dados simplificado utilizando o Power BI.

## Passos Realizados:

1. **Criação da Instância MySQL na Azure:**
   - Criei uma instância na plataforma Azure para hospedar o banco de dados MySQL.

2. **Criação do Banco de Dados:**
   - Utilizei a base de dados disponível no [GitHub](https://github.com/EdsonOliveira18/power_bi_analyst_sample/tree/b010c1874a183a0fb4b831e76dc68b9b872becec/M%C3%B3dulo%203) para criar o banco de dados no MySQL.

3. **Integração do Power BI com MySQL:**
   - Configurei a integração do Power BI com o banco de dados MySQL hospedado na Azure.

4. **Transformação dos Dados:**
   - Verifiquei problemas na base de dados e realizei as seguintes transformações:
     - Verifiquei cabeçalhos e tipos de dados.
     - Modifiquei valores monetários para double preciso.
     - Analisei e removi valores nulos quando necessário.
     - Identifiquei e preenchi lacunas nos gerentes e departamentos sem gerente.
     - Verifiquei horas dos projetos.
     - Separei colunas complexas.
     - Mesclei consultas de employee e department para criar uma tabela employee com nomes de departamentos.
     - Eliminei colunas desnecessárias.
     - Realizei junção de colaboradores e gerentes.
     - Mesclei colunas de Nome e Sobrenome.
     - Mesclei nomes de departamentos e localização.
     - Expliquei por que apenas utilizei a mescla em um caso específico.
     - Agrupei dados para saber quantos colaboradores existem por gerente.
     - Eliminei colunas desnecessárias de cada tabela.
