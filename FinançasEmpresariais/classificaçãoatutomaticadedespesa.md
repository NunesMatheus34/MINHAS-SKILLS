PROMPT — CLASSIFICAÇÃO AUTOMÁTICA DE DESPESAS

Você é um especialista em Contas a Pagar, Controladoria, Contabilidade Gerencial e classificação de despesas corporativas.

Estou enviando uma base contendo lançamentos financeiros com alguns campos preenchidos e outros pendentes.

Objetivo:
Usar os padrões históricos da base para sugerir automaticamente a classificação dos lançamentos pendentes.

Analise principalmente: Fornecedor_Raw, Fornecedor_Normalizado, CNPJ, Descricao_Lancamento, Valor, Moeda, Forma_Pagamento, Unidade, Projeto, Conta_Contabil, Centro_Custo, Natureza_Despesa e Status_Classificacao.

Tarefa principal:
Para todos os lançamentos com Status_Classificacao = "Pendente", sugira:
1. Conta Contábil
2. Centro de Custo
3. Natureza da Despesa
4. Nível de confiança da sugestão, de 0% a 100%
5. Justificativa objetiva da classificação
6. Indicação se precisa ou não de revisão humana

Regras de análise:
- Use os lançamentos já classificados como base de aprendizado.
- Considere variações de nomes do mesmo fornecedor.
- Não classifique apenas pelo fornecedor quando a descrição indicar outra natureza.
- Identifique descrições genéricas como NF, FATURA, SERVIÇOS DIVERSOS, CONTRATO MENSAL, DESP OPERACIONAL e similares.
- Quando houver baixa confiança, sinalize como Revisão humana obrigatória.
- Quando houver possível erro histórico na base, não replique o erro automaticamente.
- Quando o mesmo fornecedor puder ter usos diferentes, use a descrição, unidade, projeto e centro de custo histórico como apoio.
-Utilize a aba “DE PARA” como apoio para as classificações necessárias

Entregáveis:
1. Tabela com todos os lançamentos pendentes classificados.
2. Coluna de justificativa para cada sugestão.
3. Coluna com nível de confiança.
4. Tabela separada apenas com os casos que exigem revisão humana.
5. Ranking dos fornecedores com maior volume financeiro pendente.
6. Resumo por Conta Contábil sugerida.
7. Resumo por Centro de Custo sugerido.
8. Resumo por Natureza de Despesa sugerida.
9. Lista de regras automáticas que a empresa poderia implementar no ERP para reduzir classificação manual.

Formato de resposta:
Responda em tabelas organizadas e, ao final, traga um resumo executivo com os principais riscos e recomendações. Quero que tudo esteja contemplado em um único arquivo em Excel
