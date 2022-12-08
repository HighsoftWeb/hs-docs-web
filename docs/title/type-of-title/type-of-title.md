---
id: type-of-title
title: Tipo de Título
sidebar_position: 2
sidebar_label: Gerais
tags:
  - type of title
  - tipo de título
  - cadastro
  - consulta
  - exclusão
  - edição
  - gerais
---

## Cadastro

Para conseguir criar um tipo de título devemos ir no [menu](../intro/getting-started#navegação) <highlight bgColor="#54638c">Cadastro > Financeiro > Tipo de Títulos</highlight>.

:::info
[Não encontrei esse menu](../../intro/getting-started#não-encontrei-o-menu-desejado)
:::

Dentro do cadastro de tipos de títulos devemos clicar no botão `Novo` e começar a preencher as informações.

- **Cod. Tipo Título:** Abreviação do tipo de título que deseja criar com no máximo 3 caracteres. **Ex:** CC para Cartão de Crédito.
- **Descrição:** Nome do Tipo de Título que deseja criar.
- **Situação:** Campo para ativar ou inativar um Tipo de Título. (Para a criação sempre manter ativado)
- **Abreviatura:** Abreviar a descrição criada referente ao nome do Tipo de Título criado.
- **% Acrésc. Comissão:** Pode ser utilizado como forma de acrescer uma % na comissão do representante no momento da venda. (Usado somente caso utilize o módulo de comissão)
- **Espécie:** Deve ser utilizado uma espécie compatível com o Tipo de Título. (**Ex:** Espécie dinheiro para o Tipo de Título DN.)
- **Float Bancário:** Número de dias úteis que o banco retém os valores recebidos por esta carteira, para então disponibilizar em sua conta-corrente.
- **Cod. Cliente Bandeira:** Utilizado quando o cliente deseja que o título gere para outro cliente no financeiro. (**Ex:** Quando vendido para Consumidor Final e este paga via CC. Caso esteja cadastrado um Cliente Bandeira o sistema em vez de gerar um título para consumidor final, seria gerado para o Cliente Bandeira. Dessa forma conseguimos controlar os valores recebidos via máquina de cartão de crédito.)
- **Vlr.% Despesa:** Caso utilizarmos um Tipo de Título como CC ou CD possivelmente teríamos uma taxa de despesa. Esse seria o campo para alocarmos esse % de despesa.
- **Crédito/Débito:** Informação utilizada para os Tipos de Título com espécie para Cartão.
- **Intervalos Dias:** Intervalo de dias padrão para o Tipo de Título. (**Ex:** Para CD(cartão de débito) poderíamos alocar o número 1 no campo. Então o sistema sempre jogaria o título com 1 dia a frente da emissão.)
- **Tecla Atalho:** Tecla de atalho para uso no Frente de Caixa.
- **Conta Gerencial:** Código criado no plano de conta gerencial referente a DRE.
- **Abater Titulos Receber:**
- **Considerar Desconto:**
- **Disp.Móvel:** Flag que cria vinculo para usuários do HSMóvel.
- **Ativo Finalizadora:** Flag que cria vinculo entre a tela finalizadora utilizada nas baixas por composição e caso configurada finalizadora para processamento de orçamentos.
- **Considerar Acréscimo Financeiro na Devolução:**

:::warning
Devemos tomar cuidado ao vincularmos a espécie no momento de criar um Tipo de Título, pois estes ditarão as regras sobre processamentos alimentando caixa e financeiro. Um Tipo de Título criado errado pode furar valores de caixa.
:::

## Consulta

### Pesquisa

## Exclusão

## Edição