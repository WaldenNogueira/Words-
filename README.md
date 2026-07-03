# Words PWA v5

Versão com visual mais próximo do Notion: menos sombra, cards mais limpos, espaçamento corrigido e tipografia mais leve.

## Atualizações da v5

- Visual mais minimalista, com estilo de bloco/card inspirado em Notion.
- Tipografia e espaçamentos revisados.
- Removidos os botões de exportar e importar.
- Novo botão GPT no formulário.
- Novo botão GPT nos cards salvos para criar uma query pronta quando faltar tradução, definição ou exemplo.
- Mantém os dados salvos da v3/v4 porque usa a mesma chave de armazenamento local.

## Como atualizar no GitHub Pages

1. Extraia este ZIP.
2. Envie para o repositório estes arquivos na raiz:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Faça commit.
4. Abra o app com `?v=5` no final da URL para forçar atualização.

Exemplo:
`https://waldennogueira.github.io/Words-/?v=5`

## Observação

O botão GPT copia uma query pronta e tenta abrir/compartilhar com o ChatGPT. Em alguns celulares, ele abre a folha de compartilhamento do Android; em outros, ele abre o ChatGPT no navegador.
