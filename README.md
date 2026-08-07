# Roteiro China

Seminário de Capacitação sobre Inovação Cultural e Integração da Diversidade no Brasil no Âmbito da Iniciativa de Civilização Global.

**Página publicada:** `https://SEU-USUARIO.github.io/NOME-DO-REPO/`
_(troque pelo link real depois de ativar o GitHub Pages — veja abaixo)_

## O que tem aqui

Este repositório reúne o cronograma completo da viagem (09 a 25 de agosto de 2026 — Pequim, Hangzhou e Huzhou), voos de ida e volta, e informações úteis para quem vai participar do seminário.

Todo o conteúdo está em um único arquivo, `index.html`, publicado como site estático via GitHub Pages.

## Como ativar/atualizar a página publicada

1. **Settings → Pages → Build and deployment → Deploy from a branch**
2. Branch: `main`, pasta: `/ (root)`
3. Salvar. O link fica disponível em poucos minutos em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`

Para atualizar o conteúdo, basta editar `index.html` e dar `git push` — não há build nem dependências.

## Editando o cronograma ou as informações úteis

Todo o conteúdo (datas, horários, voos, cartões de informações úteis) está direto no HTML, em português, fácil de localizar por busca de texto (Ctrl+F) no próprio arquivo:

- Voos → seções `<section class="flights">`
- Dias e atividades → seção `<section class="timeline">`, um bloco `<div class="day">` por dia
- Informações úteis (documentos, clima, moeda, hospedagem, contatos, conectividade) → seção `<section class="info">`, hoje marcadas como _"a preencher"_

## Estrutura

```
.
├── index.html   # site completo (cronograma, voos, informações úteis)
└── README.md    # este arquivo
```
