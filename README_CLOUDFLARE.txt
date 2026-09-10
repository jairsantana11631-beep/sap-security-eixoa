SAP SECURITY EIXO V13 - CLOUDFLARE FREE

Estrutura preparada para Cloudflare Pages.
1. Crie uma conta Cloudflare Free.
2. Workers & Pages > Create > Pages > Direct Upload ou Git.
3. Publique esta pasta.
4. Em Settings > Functions > KV namespace bindings, crie um namespace KV e associe com o nome APP_DATA.
5. Faça um novo deploy.

Endpoints:
/threat-intel - NVD + CISA KEV, sem OpenAI
/cve-alerts-api - cadastros em Workers KV
/media-api - PDFs/mídia pequena em Workers KV

O index.html permanece como o portal navegável.
