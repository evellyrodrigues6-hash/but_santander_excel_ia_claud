# Calculadora de Investimentos em FIIs

## Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático de Excel. A proposta foi criar uma ferramenta para simular investimentos em Fundos Imobiliários (FIIs), mostrando como o patrimônio pode crescer ao longo do tempo com aportes mensais e rendimentos.

A planilha permite simular diferentes períodos de investimento e visualizar uma sugestão de distribuição dos aportes de acordo com o perfil do investidor.

## O que a planilha permite fazer?

Com a ferramenta, é possível:

- Simular o patrimônio acumulado ao longo dos anos;
- Calcular o valor futuro dos investimentos;
- Visualizar os rendimentos estimados da carteira;
- Comparar a distribuição dos investimentos entre diferentes perfis;
- Consultar uma sugestão de investimento com base no salário informado.

Os resultados aparecem nos campos de patrimônio, rendimento da carteira e distribuição dos investimentos na própria planilha.

## Funções utilizadas

### VF (Valor Futuro)

Utilizei a função `VF` para calcular o patrimônio futuro, considerando a taxa mensal de rendimento, o período do investimento e os aportes realizados.

Ela ajuda a entender quanto o dinheiro pode acumular ao longo do tempo, considerando os juros compostos.

### PROCV

A função `PROCV` é utilizada para buscar os percentuais de distribuição dos investimentos em uma tabela de apoio, de acordo com o perfil selecionado.

Com esses percentuais, a planilha calcula a sugestão de distribuição do valor destinado aos investimentos.

## Intervalos nomeados

Para facilitar a organização das fórmulas, foram utilizados os seguintes intervalos nomeados:

- `aporte`: valor do investimento mensal;
- `taxa_mensal`: taxa de rendimento mensal;
- `patrimonio`: patrimônio calculado na simulação;
- `qtde_anos`: período do investimento;
- `rendimento_carteira`: rendimento estimado da carteira;
- `salario`: salário informado na ferramenta;
- `sugestao_investimento`: valor sugerido para investir.

Esses nomes ajudam a identificar as informações utilizadas nos cálculos e tornam as fórmulas mais fáceis de entender.

## Perfis de investidor

A planilha trabalha com três perfis de investidor: conservador, moderado e agressivo. Cada perfil possui percentuais específicos para a distribuição dos investimentos, conforme o exemplo apresentado na atividade.

O gráfico de pizza permite visualizar como o aporte é dividido entre as categorias de investimento de acordo com o perfil selecionado.

Dessa forma, é possível comparar as estratégias de distribuição e entender como cada perfil influencia a composição da carteira.

## Alterações em relação à ferramenta do Expert

Mantive a ferramenta conforme o modelo apresentado pelo Expert, sem realizar alterações na estrutura ou nas funcionalidades.

Durante a atividade, o foco foi acompanhar o funcionamento da planilha e compreender como as funções do Excel são utilizadas para realizar as simulações.

## Prints da planilha

### Simulação com o perfil moderado

Aqui está uma captura de tela da planilha preenchida com o primeiro perfil de investidor.

<img width="1280" height="720" alt="Moderado" src="https://github.com/user-attachments/assets/8f4c225e-ea62-4bcd-ac4c-e604ca5c23f7" />



### Simulação com o perfil agressivo

Nesta imagem, é possível comparar os resultados utilizando outro perfil de investidor, mantendo os mesmos dados da simulação.

<img width="1280" height="720" alt="Agressivo" src="https://github.com/user-attachments/assets/00472040-4fad-40c4-9b16-bfa91a055d59" />


## O que aprendi

Com este projeto, pratiquei o uso das funções `VF` e `PROCV`, a criação de intervalos nomeados e a construção de simulações financeiras no Excel.

Também pude entender melhor como organizar os dados de uma planilha e utilizar fórmulas para apresentar resultados que ajudam no planejamento financeiro.

## Ferramentas utilizadas

- Microsoft Excel
- Funções financeiras e de pesquisa
- Intervalos nomeados
- Seleção entre os perfis conservador, moderado e agressivo
- Gráfico de pizza para visualizar a distribuição dos aportes conforme o perfil escolhido

## Projeto desenvolvido durante os estudos

Este projeto faz parte da minha prática de Excel e tem como objetivo aplicar os conhecimentos adquiridos em uma atividade voltada para simulação de investimentos.
