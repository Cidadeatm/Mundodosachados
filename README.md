# Mundo dos Achados

Página de captura responsiva, com logo, imagens ilustrativas e botão para entrar no grupo.

## Hospedagem

Site estático, sem instalação de dependências e sem comando de build. A pasta de publicação é a raiz do repositório (`.`).

- **GitHub Pages:** em Settings → Pages, selecione Deploy from a branch, branch `main`, pasta `/ (root)` e salve.
- **Netlify:** importe o repositório; deixe o comando de build vazio e use `.` como diretório de publicação.
- **Vercel:** importe o repositório como projeto Other, sem comando de build e com saída `.`.
- **Hospedagem tradicional:** envie `index.html` e as duas imagens para a pasta pública do site, mantendo os três arquivos juntos.

## Editar

Abra `index.html` para alterar os textos e estilos. O destino do botão está na constante `GROUP_URL` e já aponta para o link oficial enviado:

https://api.zapiz.com.br/functions/v1/public-redirect?slug=mundodosachados

As imagens de produtos são ilustrativas. A logo foi fornecida pelo proprietário.
