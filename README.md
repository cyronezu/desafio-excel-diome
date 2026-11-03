# desafio-excel-diome
Dashboard desenvolvido no Microsoft Excel para transformar uma base de assinaturas Xbox em indicadores e visualizações comerciais. Projeto de portfólio de análise de dados.

# Base utilizada
Arquivo Excel fornecido no desafio, com 295 registros e 13 campos, incluindo identificador, cliente, plano, data de início, renovação automática, preço, modalidade de assinatura, adicionais, cupom e valor total. Os dados foram mantidos na aba Base de Dados do arquivo entregue.
Atenção: a fonte não especifica a moeda; a apresentação usa R$ como convenção visual. Total Value foi interpretado como valor líquido por registro. Não há informações suficientes para calcular receita recorrente efetivamente recebida, churn ou LTV.

# Principais indicadores
- Receita líquida registrada: soma de Total Value.
- Assinaturas: contagem de identificadores na base.
- Ticket médio: receita líquida / número de registros.
- Descontos concedidos: soma de Coupon Value.
- Renovação automática: quantidade e proporção de registros marcados como Yes.
- Mix de planos: quantidade e receita líquida por Plan.
- Modalidades: quantidade por Subscription Type.
- Adicionais: adesões a EA Play e Minecraft Season Pass.
- Evolução mensal: receita líquida agrupada pelo mês da data de início da assinatura (coorte de início, não receita mensal recebida).

 # Estrutura do arquivo
- Dashboard: KPIs e quatro gráficos de desempenho.
- Indicadores: fórmulas e tabelas de apoio aos gráficos.
- Base de Dados: registros de origem organizados em tabela.
- Leia-me: definições e orientações dentro do próprio Excel.
