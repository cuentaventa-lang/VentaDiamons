DIAMONDHUB - CLOUDFLARE

Estructura:
public/index.html
wrangler.jsonc

Para Cloudflare Workers:
1. Conecta el repositorio de GitHub.
2. Asegura que public/index.html exista.
3. Usa como comando de despliegue:
   npx wrangler deploy
4. Si Cloudflare pide una carpeta de assets, usa:
   public

No subas a GitHub ninguna sb_secret_... ni otros secretos.
