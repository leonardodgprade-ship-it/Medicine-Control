---
title: Controle de Medicação
---

# Controle de Medicação

Um app simples para registrar as doses de remédio da minha filha e saber, de relance, quando a próxima está liberada.

## Abrir o app

**[➜ Abrir o Controle de Medicação](./controle-medicacao.html)**

Funciona direto no navegador, sem instalação. Dá pra adicionar à tela inicial do celular pra abrir como um app (veja abaixo).

## O que ele faz

- Registra cada dose: medicamento, quantidade, unidade, horário e observações
- Mostra um anel de contagem para medicamentos com intervalo definido (ex.: a cada 6h), indicando quando a próxima dose está liberada
- Histórico completo, agrupado por dia, com opção de excluir um registro
- Backup manual (ícone ⇅): copia todos os dados como texto para guardar em outro lugar, e permite restaurar colando esse texto de volta

## Como os dados são salvos

Os registros ficam salvos no `localStorage` do navegador — ou seja, **no navegador e aparelho que você está usando no momento**. Isso significa que:

- Os dados não aparecem automaticamente em outro navegador ou celular
- Limpar os dados de navegação/cookies desse site apaga o histórico
- Para levar os dados de um aparelho para outro, ou para ter uma cópia de segurança, use o backup manual (ícone ⇅ dentro do app)

## Adicionar à tela inicial (opcional)

**iPhone (Safari):** abra o link → toque em Compartilhar → "Adicionar à Tela de Início".

**Android (Chrome):** abra o link → menu (⋮) → "Adicionar à tela inicial".

Assim ele abre em tela cheia, como um app de verdade.

## Publicar este projeto no GitHub Pages

1. Crie um repositório e suba os arquivos `index.md` e `controle-medicacao.html` na raiz.
2. Vá em **Settings → Pages**, escolha a branch (geralmente `main`) e a pasta `/ (root)`.
3. O site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

---

*Ferramenta pessoal — não é um app médico e não recomenda doses.*
