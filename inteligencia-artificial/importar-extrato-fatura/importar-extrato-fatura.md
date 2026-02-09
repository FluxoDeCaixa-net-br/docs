---
title: "Importar extrato e fatura"
---

#### Importação de Extratos Bancários e Faturas de Cartão de Crédito

Agora é possível importar extratos bancários ou faturas de cartão de crédito diretamente para o sistema, a partir de qualquer banco. Os formatos suportados são:

- **PDF**
- **CSV**
- **Excel**
- **OFX**

<Tip>
Arquivos nos formatos CSV, Excel ou OFX são processados mais rapidamente do que arquivos PDF.
</Tip>

**Como importar:**

1. Acesse o site ou app do seu banco ou operadora do cartão e exporte o extrato/fatura.
2. No Fluxo de Caixa, vá em **"Importar Extrato e Fatura"**.
3. Adicione um novo arquivo.
4. Faça o mapeamento entre os dados do arquivo e os registros do sistema.
5. Revise as informações e conclua a importação.

O sistema tenta fazer o mapeamento automaticamente com base em data, valor e descrição. Você pode:

- **Criar uma nova conta** (caso ela ainda não exista no sistema).
- **Realizar uma baixa** de uma conta já registrada.
- **Ignorar o item** (ideal para lançamentos duplicados ou transferências internas).

<Warning>
Evite importar o **total da fatura** ou o **pagamento da fatura** para não duplicar valores. Marque esses registros como "Ignorar".
</Warning>

---

## Dicas Importantes

### Movimentações entre Contas

Ao importar extratos que envolvam **transferências internas**, como:

- Conta corrente para conta poupança;
- Contas em diferentes bancos da mesma empresa;

Utilize a opção **"Ignorar"** no mapeamento. Isso evita que essas movimentações apareçam como despesas ou receitas, mantendo seu fluxo de caixa consistente.

### Faturas de Cartão de Crédito

Se for importar uma **fatura de cartão de crédito**, evite importar registros como:

- **Total da fatura**
- **Pagamento da fatura**

Esses lançamentos já estão representados pelas despesas detalhadas. Importá-los novamente resultará em **valores duplicados**.

#### Exemplo:

| Transação | Valor | Status Recomendado |
| --- | --- | --- |
| Despesa 1 | R\$100 | ✅ Importar |
| Despesa 2 | R\$650 | ✅ Importar |
| **Total da Fatura** | R\$750 | ⚠ Ignorar |
| **Pagamento da Fatura** | R\$750 | ⚠ Ignorar |

#### Alternativa:

Se quiser controlar se a fatura foi paga, você pode registrar o **Total da Fatura com valor realizado igual a R\$0**:

- Mantém o controle do pagamento.
- Evita duplicidade de valores no sistema.

---

### Utilize o Recurso de Mesclar Contas

O sistema permite **mesclar registros semelhantes** para manter sua lista de contas mais limpa, organizada e fácil de gerenciar. Ideal para consolidar lançamentos duplicados ou com pequenas variações de descrição.

### O Sistema Salva Tudo Automaticamente

Ao fazer o mapeamento de dados, **todas as suas ações são salvas automaticamente**, passo a passo. Isso é especialmente útil se você estiver lidando com extratos longos:

- Não é necessário concluir o processo de uma vez.
- Você pode sair e retomar mais tarde sem perder nenhum progresso.

---

### Use Diretamente o Recurso de Revisão (Modo Avançado)

Mapear cada conta individualmente é fácil e ideal para iniciantes. No entanto, conforme você ganha experiência, recomendamos **pular diretamente para a tela de revisão tabular**. Esse modo permite:

- Ver todos os dados de uma vez;
- Realizar ações em lote;
- Aumentar a produtividade no mapeamento.

Você também pode unir (mesclar) registros semelhantes para facilitar o controle e evitar duplicidades. Confira com mais detalhes aqui: [https://www.youtube.com/watch?v=Ll5DKzDAyfg](https://www.youtube.com/watch?v=Ll5DKzDAyfg)
