# Lead Finder — Vercel

Site para buscar leads públicos no Google Maps sem API paga, usando Chromium headless dentro de uma Vercel Function.

## Publicar
1. Crie um repositório no GitHub e envie todos estes arquivos.
2. Na Vercel, clique em **Add New > Project**.
3. Importe o repositório.
4. Framework Preset: **Other**.
5. Clique em **Deploy**.

Não precisa configurar chave de API nem variável de ambiente.

## Observações
- O máximo da interface foi limitado a 20 leads por execução para reduzir chance de timeout.
- Google pode bloquear requisições vindas de datacenters. Se isso acontecer, tente novamente; para uso pesado, um navegador/servidor persistente é mais confiável que serverless.
- O botão de WhatsApp só aparece quando há telefone e já abre a mensagem pré-preenchida. Isso não confirma previamente se o número possui conta no WhatsApp.
