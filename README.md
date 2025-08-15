
# CFlow Design & Marketing

Sítio estático pronto para publicar no **Vercel** e **GitHub Pages**.

## Estrutura
- `index.html` (home)
- `services/` (páginas de serviços)
- `portfolio/` (grade de projetos)
- `contact.html` (contato)
- `assets/css/styles.css` (estilos)
- `assets/js/main.js` (WhatsApp link)
- `assets/img/*` (imagens e mockups)

## Deploy — GitHub Pages
1. Crie um repositório no GitHub chamado `cflow-site` em `cflowdesign`.
2. Envie todos os arquivos desta pasta para o repositório (raiz).
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch** e branch `main`, pasta `/ (root)`.
4. O site vai aparecer em: `https://cflowdesign.github.io/cflow-site/`.

## Deploy — Vercel
1. Acesse o Vercel com sua conta conectada ao GitHub.
2. Clique em **New Project** e selecione o repositório `cflow-site`.
3. Framework: **Other** (estático). Build command: **None**. Output directory: **/**.
4. Deploy. O domínio ficará algo como `https://cflow.vercel.app` (ou nome que escolher).
