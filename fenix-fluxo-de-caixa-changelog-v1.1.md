# Fênix | Fluxo de Caixa — Changelog

## v1.1 — criada em 02/11/2026 · modificada em 02/11/2026

- O app passa a se chamar **Fênix | Fluxo de Caixa**, com o ícone oficial (a arte enviada, sem alterações) no cabeçalho, na abertura, no login, no Sobre, no favicon e no manifesto.
- **Importar extrato do banco** (OFX e CSV): confere cada movimento antes de gravar, sugere dar baixa em lançamentos em aberto, cria os novos já pagos ou recebidos, aprende a categoria, avisa de possível duplicata e reconhece movimentos já importados (reimportar não duplica). Entende CSV com colunas Débito/Crédito separadas, valores com sinal invertido (fatura de cartão) e arquivos em UTF-8 ou Windows-1252.
- **Limite de gasto por categoria**: limite mensal por categoria de débito (Cadastros), barras no Dashboard dos débitos e alertas de atenção (a partir de 80%) e de estouro.
- Links dos **Termos de Uso** e da **Política de Privacidade** na abertura e em Sobre.
- Backup com novo identificador do app, compatível com os backups da v1.0; o backup agora leva também os limites, os movimentos importados e as categorias aprendidas.
- Correções: lista de lançamentos que passava da largura em telas de 360 px, título do cabeçalho cortado e aviso de formulário na abertura.
- Os dados da v1.0 neste aparelho continuam valendo (mesmo armazenamento).

## v1.0 — criada em 01/11/2026 · modificada em 02/11/2026

Primeira versão do aplicativo (então chamado Fênix | Controle Financeiro).

- Débitos: cartão de crédito (compra parcelada com parcela atual, compra única e fatura), aluguel, energia, água, internet e outras despesas, com localização, recorrência e classificação (fixa, parcela, outra).
- Créditos: entradas recebidas e recebíveis previstos, recorrentes ou não, com confirmação integral, parcial, não recebido, adiar e nova previsão.
- Pergunta diária "Houve alguma entrada de capital hoje?" e resumo do dia.
- Dois saldos sempre separados: realizado (dinheiro disponível) e projetado (estimativa).
- Dashboard dos débitos e dos créditos, com filtros e todos os indicadores clicáveis.
- Barra de quitação do mês e barra de recebíveis previstos, com o próximo vencimento e o próximo recebimento.
- Fluxo de caixa: calendário financeiro, linha do tempo (dia, semana, mês, ano) e lista, com aviso de risco de saldo negativo.
- Análise de comprometimento da renda: percentual, divisão por tipo de obrigação, comparativo mês a mês e evolução.
- Extratos com filtros, exportação em CSV e PDF e impressão.
- Alertas com antecedência configurável.
- Saldo inicial, ajuste de saldo com histórico, ocultar valores, senha opcional do aparelho.
- Cadastros livres de categorias, localizações, instituições e cartões.
- Backup e restauração em JSON (esquema v1, com campo de origem externa para integrações futuras).
- Histórico de alterações de cada lançamento; nada é apagado ao editar ou cancelar.
- Manual e changelog dentro do app, para ler e baixar.
