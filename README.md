# Projeto Final ICD

Projeto final da disciplina de Introdução a Ciência de Dados ministrado pelo professor Yuri Malheiros pela Universidade Federal da Paraíba.

# Sumário
- [Integrantes](#integrantes)
- [Dicionário dos Dados](#dicionário-dos-dados)
- [Hipóteses](#hipóteses)
- [Conclusão](#conclusão)
- [Próximos Passos](#próximos-passos)
- [Referências](#referências)

## Integrantes
Matrícula | Nome
--- | ---
20220007070 | Gustavo Souza Barros de Araújo
00000000000 | Gustavo Johan
00000000000 | Serpa
20220128745 | Fábio Soares de Lima

# Dicionário dos Dados
##### DATASET - IMÓVEIS SÃO PAULO
| Código da variável | Descrição |
| --- | --- |
Rua | Localização da rua de onde o imóvel pertence
Bairro | Bairro onde imóvel está localizado
Cidade | Cidade onde imóvel está localizado
Metragem | Área em metros quadrado
Quartos | Número de quartos no imóvel
Banheiros | Número de banheiros no imóvel
Vagas |  Vagas de estacionamento por veículo
Valor | Preço da casa que está em moeda brasileira BRL

##### DATASET - IBGE
| Código da variável | Descrição do setor |
| --- | --- |
Cod_setor           | ID
Cod_Grandes_Regiões | Código das Grandes Regiões (Regiões Geográficas)
Nome_Grande_Regiao  | Nome das Grandes Regiões (Regiões Geográficas)
Cod_UF              | Código da Unidade da Federação
Nome_da_UF          | Nome da Unidade da Federação
Cod_meso            | Código da mesorregião
Nome_da_meso        | Nome da mesorregião
Cod_micro           | Código da microrregião
Nome_da_micro       | Nome da microrregião
Cod_RM              | Código da região metropolitana ou RIDE
Nome_da_RM          | Nome da região metropolitana ou RIDE
Cod_municipio       | Código do município
Nome_do_municipio   | Nome do município
Cod_distrito        | Código do distrito
Nome_do_distrito    | Nome do distrito    
Cod_subdistrito     | Código do subdistrito
Nome_do_subdistrito | Nome do subdistrito
Cod_bairro          | Código de bairro
Nome_do_bairro      | Nome do bairro
Situacao_setor      | Código de situação do setor
Tipo_setor          | Tipo ( Situação urbana / Situação rural ) 
V001                | Domicílios particulares permanentes ou pessoas responsáveis por domicílios particulares permanentes
V002                | Moradores em domicílios particulares permanentes ou população residente em domicílios particulares permanentes
V003                | Média do número de moradores em domicílios particulares permanentes (obtida pela divisão de Var2 por Var1)
V004                | Variância do número de moradores em domicílios particulares permanentes
V005                | Valor do rendimento nominal médio mensal das pessoas responsáveis por domicílios particulares permanentes (com e sem rendimento)
V006                | Variância do rendimento nominal mensal das pessoas responsáveis por domicílios particulares permanentes (com e sem rendimento)
V007                | Valor do rendimento nominal médio mensal das pessoas responsáveis por domicílios particulares permanentes (com rendimento)
V008                | Variância do rendimento nominal mensal das pessoas responsáveis por domicílios particulares permanentes (com rendimento)
V009                | Valor do rendimento nominal médio mensal das pessoas de 10 anos ou mais de idade (com e sem rendimento)
V010                | Variância do rendimento nominal mensal das pessoas de 10 anos ou mais de idade (com e sem rendimento)
V011                | Valor do rendimento nominal médio mensal das pessoas de 10 anos ou mais de idade (com rendimento)
V012                | Variância do rendimento nominal mensal das pessoas de 10 anos ou mais de idade (com rendimento)

## Perguntas
1. **Quais os bairros onde os imóveis são mais valorizados, na média?**
2. **Qual o preço médio do m2 nos bairros mais valorizados?**
3. **Cerca de 80% dos imóveis estão abaixo dos R$ 2.000.000,00 de reais?**
4. **A coluna metragem possui um valor de correlação de Pearson forte com o preço do imóvel (pelo menos 0.6)?**
5. **Quais são os imóveis que apresentam as melhores oportunidades de negócio, Ou seja, preço abaixo da mediana de preços do seu bairro?**
6. **Para cada unidade acrescida na quantidade de 'Quartos', o preço médio dos imóveis aumenta em 10%?**

## Conclusão

## Próximos Passos

## Referências
- [DATASET - IMÓVEIS SÃO PAULO](https://gist.githubusercontent.com/tgcsantos/3bdb29eba6ce391e90df2b72205ba891/raw/22fa920e80c9fa209a9fccc8b52d74cc95d1599b/dados_imoveis.csv)
- [DATASET - IBGE](https://gist.githubusercontent.com/tgcsantos/85f8c7b0a2edbc3e27fcad619b37d886/raw/a4954781e6bca9cb804062a3eea0b3b84679daf4/Basico_SP1.csv)