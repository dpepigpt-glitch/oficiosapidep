# Sistema de Ofícios — DPE-PI

Sistema simplificado de geração de ofícios da Defensoria Pública do Estado do Piauí.
Aplicação de página única (`index.html`), sem servidor e sem senhas — todos os dados
ficam salvos apenas no navegador (localStorage).

## Como funciona

**Entrada (sem senha):** o(a) defensor(a) informa nome, cargo, nome da Defensoria,
cidade (sugerida automaticamente a partir do nome da Defensoria), sigla opcional para
o número do ofício, telefone e e-mail. Esses dados aparecem no cabeçalho, no fecho e
nos contatos de todos os ofícios gerados.

## Modalidades de ofício

1. **2ª Vias e Inteiro Teor** — solicitação de 2ª via de certidão de nascimento,
   casamento e óbito, e certidão de inteiro teor, com um ou mais documentos/titulares
   por ofício.
2. **Alteração de Patronímico** — retificação do registro civil de nascimento em razão
   de alteração do nome do genitor ou da genitora por casamento ou divórcio
   (art. 33, XXIV, da LC 59/05 e art. 110, I, da Lei 6.015/73).

## Outros recursos

- Numeração sequencial sugerida automaticamente (editável).
- Data do ofício sempre é a data atual, com cidade extraída do cadastro.
- Histórico local dos ofícios gerados, com reimpressão e exclusão.
- Impressão em A4 pelo próprio navegador (Ctrl+P é acionado automaticamente).
