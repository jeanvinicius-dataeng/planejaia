# PlanejaIA

Assistente financeiro pessoal que funciona pelo WhatsApp. A pessoa escreve ou fala o gasto do jeito dela, a IA interpreta a mensagem e um painel web mostra saldo, parcelas, contas fixas e projeções.

**Status: protótipo de portfólio.** Os dados, valores e planos que aparecem nas telas são de exemplo.

## Ver funcionando

- Página do produto: https://jeanvinicius-dataeng.github.io/planejaia/
- Painel de demonstração: https://jeanvinicius-dataeng.github.io/planejaia/app.html

No painel, qualquer e-mail e qualquer PIN de 4 dígitos entram. Nada é enviado para servidor, tudo fica só no navegador de quem abre.

## O que tem neste repositório

| Arquivo | O que é |
| --- | --- |
| `index.html` | Página de apresentação do produto, com a conversa do WhatsApp animada |
| `app.html` | Painel financeiro (início, extrato, categorias, gastos fixos, agenda e carteira) |

Cada tela é um único arquivo HTML, sem etapa de build.

## O que o painel faz

- Saldo do período, entradas e saídas
- Extrato com categoria e forma de pagamento
- Parcelas do cartão com acompanhamento do que já foi pago
- Contas recorrentes com dia de vencimento
- Gráficos por categoria e por semana
- Exportação de relatório

## Tecnologias

- HTML, CSS e JavaScript puro
- Chart.js para os gráficos
- Tabler Icons

O protótipo completo, com o robô do WhatsApp, foi construído com Node.js, SQLite, Gemini API e Evolution API. Este repositório guarda a parte visual.

## Autor

Jean Vinicius Mendes da Costa

- Portfólio: https://jeanvinicius-dataeng.github.io
- LinkedIn: https://www.linkedin.com/in/jeanvinicius
