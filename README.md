# CrediFlow — Demo visual

Protótipo navegável de uma PWA para gestão de empréstimos pessoais, lançamentos e agenda de cobranças.

## Fluxos desta versão

- Cadastro manual de empréstimos;
- Taxa de juros informada por operação;
- Prazos de 7, 15, 30, 45, 60 e 90 dias;
- Prévia de juros compostos;
- Registro de recebimentos do dia;
- Fechamento diário com novos empréstimos, recebimentos e cobranças;
- Prévia de relatório para envio no WhatsApp;
- Agenda de cobrança;
- Atribuição de cobranças aos funcionários;
- Notificação simulada da equipe;
- Dados fictícios e layout responsivo.

## Link online

https://marqueskaio.github.io/empresta-demo/

## Importante

É uma demo visual. Não há login real, persistência, integração com WhatsApp, notificações reais ou movimentação financeira.

A fórmula exibida na prévia é ilustrativa: `montante = principal × (1 + taxa)^(prazo/30)`. A unidade da taxa e a periodicidade definitiva precisam ser confirmadas antes da implementação real.