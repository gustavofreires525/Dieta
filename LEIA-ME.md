# DIETA — como publicar de graça (3 minutos) e usar em qualquer aparelho

## 1) Publicar o site (GitHub Pages, sem domínio pago)
1. Crie uma conta grátis em github.com (se ainda não tiver).
2. Clique em **+ → New repository**. Nome: `dieta`. Marque **Public**. Clique em **Create repository**.
3. Na página do repositório, clique em **uploading an existing file** e arraste TODOS estes arquivos de uma vez:
   `index.html, manifest.webmanifest, sw.js, content.json, version.json, icon-192.png, icon-512.png`
   Clique em **Commit changes**.
4. Vá em **Settings → Pages**. Em **Branch**, escolha `main` e `/ (root)` e clique em **Save**.
5. Em 1–2 minutos o endereço aparece: `https://SEU-USUARIO.github.io/dieta/` — é o seu site. Grátis, sem domínio.

> Seus dados pessoais NÃO ficam no repositório (só o código do site). Se preferir, o repositório pode ficar público sem problema.

## 2) Ligar a sincronização (mesmos dados em qualquer aparelho)
1. No site: **Config. → Sincronizar entre aparelhos → “Clique aqui para criar a chave”**.
2. No GitHub, deixe marcada só a permissão **gist**, validade **No expiration**, **Generate token**, copie a chave (`ghp_...`).
3. Cole no site e clique **Conectar**. O selo “☁️ Salvo na nuvem” aparece no canto.
4. Em outro aparelho: no primeiro, clique **Copiar link para outro aparelho**, abra esse link no segundo. Pronto.

Tudo é salvo sozinho a cada alteração, e cada aparelho confere novidades a cada minuto.

## 3) Instalar como app no celular
- Android (Chrome): menu ⋮ → **Instalar app**.
- iPhone (Safari): botão compartilhar → **Adicionar à Tela de Início**.

## 4) Atualizações
- O site se atualiza sozinho quando você publica arquivos novos (ele detecta a nova versão e recarrega).
- Histórias e promoções vêm do arquivo `content.json`: substitua esse arquivo no GitHub e todos os aparelhos recebem.
- Alimentos: TACO (embutida) + Open Food Facts + USDA, consultados online na hora da busca.
