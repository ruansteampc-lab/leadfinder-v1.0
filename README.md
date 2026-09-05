# Lead Finder — Vercel v1.0.1

## Publicar
1. Envie **o conteúdo desta pasta** para a raiz do repositório GitHub.
2. Na Vercel: Add New > Project > importe o repositório.
3. Framework Preset: Other.
4. Root Directory: deixe `./` (raiz).
5. Build Command / Output Directory / Install Command: deixe no padrão, sem preencher manualmente.
6. Não precisa de variável de ambiente.
7. Clique em Deploy.

## Estrutura esperada na raiz
- index.html
- package.json
- vercel.json
- api/search.js

## Correção desta versão
Removida a configuração `memory` do vercel.json. Em projetos Hobby com Fluid Compute a Vercel gerencia a memória da Function; definir memória manualmente no arquivo pode causar configuração incompatível/aviso de build.
