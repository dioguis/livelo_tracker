# Meu Controle de Pontos Livelo

Um dashboard pessoal para controlar pontos Livelo: saldo, pendências, prazos de crédito e metas.

## O problema

Pontos de parceiros Livelo raramente são creditados na hora. Uma compra pode levar até 45 dias após a entrega. Uma passagem só credita depois da viagem. No meio disso, é fácil perder o controle de quanto já está garantido, quanto está atrasado e quanto falta para bater uma meta.

Fiz esse app para resolver isso no meu próprio uso.

## O que ele faz

- Dashboard com saldo disponível, pontos pendentes, pontos em atraso e próximos créditos
- Cálculo automático da data prevista de crédito (7, 15, 30, 45, 60, 90 dias ou prazo personalizado)
- Metas com cálculo de quanto acumular por mês, separando o que a assinatura já garante do que precisa vir de compras e promoções
- Simulador de metas e cenários (conservador, realista, agressivo)
- Calendário de créditos, gráficos de evolução e origem dos pontos, alertas de atraso e de ritmo da meta
- Um único arquivo HTML, sem backend, sem banco de dados. Os dados ficam salvos no navegador (localStorage), com opção de exportar e importar backup em JSON

## Stack

HTML, CSS e JavaScript puro, com Chart.js para os gráficos. Sem dependências obrigatórias, sem servidor.

## Link

*(https://dioguis.github.io/livelo_tracker/)*

## Sobre o projeto

Projeto pessoal, construído para organizar meu próprio acúmulo de pontos. Foi uma boa oportunidade de trabalhar modelagem de dados, regras de negócio, cálculo de datas e interface do zero, sem frameworks.

Sugestões são bem-vindas.
