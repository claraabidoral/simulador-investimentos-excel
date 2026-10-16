# simulador-investimentos-excel
Ferramenta de controle e simulação de investimentos em fundos imobiliários desenvolvida em Excel.
# Simulador de Investimentos em Fundos Imobiliários

Projeto desenvolvido para o desafio **Criando uma Ferramenta de Controle de Investimentos com Excel**, com o objetivo de criar uma planilha capaz de simular investimentos em fundos imobiliários.

## que a ferramenta faz

A planilha permite responder às seguintes perguntas:

- Quanto investir por mês;
- Por quantos anos investir;
- Qual a taxa de rendimento mensal;
- Quanto patrimônio será acumulado;
- Quanto será recebido em dividendos por mês.

Também são apresentados cenários de investimento para **2, 5, 10, 20 e 30 anos**.

## Função VF

A função **VF (Valor Futuro)** é utilizada para calcular o patrimônio acumulado ao longo do período, considerando o aporte mensal, a taxa de rendimento e a quantidade de meses do investimento.

Dessa forma, é possível visualizar quanto o investimento poderá acumular ao longo do tempo.

##  Função PROCV

A função **PROCV** é utilizada para consultar a tabela de perfis de investidores.

Ao selecionar um perfil, a planilha identifica automaticamente o percentual do aporte destinado a cada tipo de fundo imobiliário.

##  Perfis de investidor

Foram utilizados três perfis:

- Conservador;
- Moderado;
- Arrojado.

Cada perfil distribui **100% do aporte mensal** entre seis categorias de fundos imobiliários: Papel, Tijolo, Híbrido, FOF, Desenvolvimento e Agro.

Os percentuais utilizados possuem finalidade exclusivamente educacional e não representam recomendação de investimento.

## Configurações

A planilha possui uma área de configurações com:

- Salário mensal;
- Taxa de rendimento mensal;
- Sugestão de aporte correspondente a 30% do salário.

Também foram utilizadas referências fixas nas projeções para permitir a reprodução correta das fórmulas.

## Cenários

A ferramenta apresenta projeções de patrimônio e dividendos mensais para períodos de:

**2, 5, 10, 20 e 30 anos.**

Além disso, foi incluído um gráfico para facilitar a visualização da evolução do patrimônio.

##  Alterações realizadas

Em relação ao modelo apresentado durante o desafio, organizei a ferramenta em áreas de simulação, configurações e perfis de investidor, além de incluir um gráfico de evolução patrimonial.

## Arquivo do projeto

O arquivo Excel disponível neste repositório contém a ferramenta completa de simulação.

> Os valores e percentuais apresentados são fictícios e utilizados exclusivamente para fins educacionais.
