# Instituto Kronos · Painel — Layout Linear Dense

Hub agregador do Instituto Kronos num único arquivo HTML.

- **Versão**: v0.13-teste · Layout Linear Dense
- **Inspiração**: Admin / Power-user — tabelas com badges de tipo, info-densa, stats por escopo no header, hover mostra ações inline
- **Conteúdo**: 6 camadas (Gestão/Operação/Produtos/SOPs/Biblioteca/Conhecimento) + 7 sub-áreas de Operação + 5 produtos + Playbook Mentoria Kairós com 10 notas
- **Persistência**: localStorage (`kronos_state_v1`)

## Como rodar

```bash
python -m http.server 8000
# abrir http://localhost:8000
```

Single-file, sem build, sem dependências. Funciona offline.

## Funcionalidades

- Tabelas com colunas (#, tipo badge, nome, descrição, URL, ações)
- Stats-bar no topo de cada escopo (preenchidos, notas, links+planilhas+docs, vazios)
- Layer cards com % completion e barra de progresso
- Busca com stemmer + 200+ sinônimos
- Botão Resumo (todos os links/docs/notas em uma página)
- Modal Adicionar/Editar
- 4 abas: Gestão / Operação / Produtos / SOPs / Biblioteca / Conhecimento
