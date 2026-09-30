Prompt Detecção de Fraudes

Você é um especialista em Contas a Pagar, Auditoria Financeira, Controles Internos e Detecção de Fraudes.

Analise os 4 arquivos anexados:

1. Pagamentos de Contas a Pagar
2. Cadastro de Fornecedores
3. Colaboradores e Aprovadores
4. Logs de Alterações Cadastrais

Seu objetivo é identificar indícios de fraude, pagamentos indevidos e fragilidades no processo de contas a pagar.

Procure por:

1. Pagamentos duplicados.
2. Fornecedores com CPF/CNPJ igual ao de colaboradores.
3. Conta bancária de fornecedor igual à conta de colaborador.
4. Chave PIX de fornecedor igual à chave PIX de colaborador.
5. Fornecedores diferentes usando a mesma conta bancária.
6. Pagamentos fracionados para evitar alçada de aprovação.
7. Pagamentos aprovados acima do limite do aprovador.
8. Pagamentos para fornecedores bloqueados ou inativos.
9. Fornecedores recém-cadastrados recebendo valores relevantes.
10. Alterações de dados bancários poucos dias antes do pagamento.
11. Alterações cadastrais feitas fora do horário comercial.
12. Alterações feitas por usuários suspeitos ou desligados.
13. Pagamentos em horário atípico.
14. CNPJs/CPFs inválidos ou genéricos.
15. Pagamentos sem aprovação.

Considere que os dados estão desorganizados. Não compare apenas nomes exatos.

Use como critérios:
- CPF/CNPJ
- Código do fornecedor
- Nome aproximado
- Conta bancária
- Chave PIX
- Valor
- Data do pagamento
- Hora do pagamento
- Aprovador
- Usuário de liberação
- Logs de alteração cadastral

Apresente o resultado em tabela com:

ID do Pagamento
Fornecedor
CPF/CNPJ
Valor Pago
Data do Pagamento
Tipo de Alerta
Nível de Risco
Evidência Encontrada
Possível Impacto
Ação Recomendada

No final, gere um resumo executivo em um único arquivo em Excel com:
