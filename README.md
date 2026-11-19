# Gabriel Ferreira Lima

Página pessoal de apresentação: quem eu sou, o Nexo (meu principal projeto), outros projetos, habilidades, formação e contato.

É um site estático de um arquivo só (`index.html`), com as imagens em `img/`. As animações usam [GSAP](https://gsap.com) com ScrollTrigger, carregados de CDN, e as fontes vêm do Google Fonts. A página funciona no celular e no computador, tem tema claro e escuro, e fica sem animação para quem desliga os movimentos no aparelho.

## Ver no computador

Abra o `index.html` no navegador ou sirva a pasta:

```bash
python -m http.server 4321
```

e acesse http://localhost:4321.

## Publicar no GitHub Pages

1. Crie no GitHub um repositório público chamado `gabriel-f-lima.github.io`.
2. Envie este repositório para ele:

   ```bash
   git remote add origin https://github.com/gabriel-f-lima/gabriel-f-lima.github.io.git
   git push -u origin main
   ```

3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.

O site fica em https://gabriel-f-lima.github.io em alguns minutos.

## Imagens

As capturas em `img/` são telas do Nexo com dados de exemplo, reduzidas para 540 × 960.
