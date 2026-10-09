# Ateliê Lume Lash — SPA demo

## Iniciar
```bash
npm install
cp .env.example .env
npm run dev
```
Configure `VITE_WHATSAPP_NUMBER` no `.env` para habilitar o agendamento externo. Sem o número, os botões levam à seção de contato.

## Produção
```bash
npm run build
```
O diretório `dist/` pode ser publicado na Vercel como projeto Vite.

## Antes de publicar para uma cliente
- Substituir imagens ilustrativas de Unsplash por fotos licenciadas/autorizadas de cílios e do espaço real.
- Trocar nome, localização, textos, marca e WhatsApp pelos dados da cliente.
- Inserir avaliações reais apenas com consentimento.
- Verificar acessibilidade, links, responsividade e política de privacidade conforme coleta de dados.

Design tokens: `design-system.json`.
