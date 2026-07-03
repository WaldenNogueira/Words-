# Words PWA v4

App simples para salvar vocabulário em inglês.

## Atualizações da v4

- Cards salvos com ícones de favorito, áudio, editar e apagar no topo.
- Dropdown para tradução.
- Dropdown para exemplo.
- Design mais minimalista, com menos ruído visual e ações mais compactas.
- Mantém os dados salvos da v3 porque usa a mesma chave de armazenamento local.

## Como publicar no GitHub Pages

1. Extraia este ZIP.
2. Envie para o repositório estes arquivos na raiz:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
3. Faça commit.
4. Em Settings > Pages, use `main` e `/(root)`.
5. Abra o app com `?v=4` no final da URL para forçar atualização.

## Observação

A tradução usa MyMemory API e o dicionário usa Free Dictionary API. Eles são gratuitos e sem chave, mas podem ter limite ou falhar com algumas expressões. O app sempre deixa os campos editáveis.
