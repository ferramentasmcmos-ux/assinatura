# Gerador de assinatura de e-mail · mCMOs

Arquivo único, sem dependências de build.

## Publicar no GitHub Pages

1. Crie um repositório (ex.: `assinatura-mcmos`) e envie os arquivos desta pasta para a raiz.
2. No repositório: **Settings › Pages › Build and deployment**.
3. Em **Source**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`. Salve.
4. Em 1 a 2 minutos o gerador fica disponível em `https://<usuario>.github.io/assinatura-mcmos/`.

## Logo no Gmail

O logo vai embutido na assinatura, o que funciona no Apple Mail e no Outlook. O Gmail exige imagens em endereço público. Depois de publicar, o logo estará em:

`https://<usuario>.github.io/assinatura-mcmos/logo-mcmos-email.png`

Envie esse endereço para configurar `LOGO_URL` no gerador e gerar o `index.html` de novo.
