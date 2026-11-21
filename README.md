# speedfibraoptica.com.br

Site da Speed Internet Fibra Óptica.

Desde 21/11/2026 o site roda na VPS própria (Caddy), na pasta `/opt/monitor/caddy/speedsite`, e não mais na Netlify.
Alterações nesta branch **não** são publicadas sozinhas: depois do commit, copie os arquivos para a VPS
(sem a pasta `.git` e sem este README). O cadeado (HTTPS) é renovado automaticamente pelo Caddy.

Arquivos:
- `index.html`: o site (página única)
- `fonts/`: fonte Bricolage Grotesque servida pelo próprio site
- `img/`: imagens
- `robots.txt`, `sitemap.xml`: para o Google
- `llms.txt`: resumo da empresa para buscadores com IA
