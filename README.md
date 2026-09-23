Desenvolvimento de Geoportal Web para visualização e consulta de informações territoriais e ambientais.

👤 **Parte do portfólio de:** https://mirianniz-debug.github.io/Portfolio/

## Incorporando o geoportal em outro site (iframe)

O `index.html` é responsivo, mas isso só funciona se o `<iframe>` que o incorpora também for responsivo. Use sempre largura em porcentagem, nunca um valor fixo em pixels — um `width` fixo faz a página inteira que o hospeda estourar no celular:

```html
<iframe src="URL_DO_GEOPORTAL" style="width:100%; border:0;" height="600" loading="lazy"></iframe>
```

Evite embeds como `<iframe width="800" height="120" ...>`: uma largura fixa maior que a tela do celular obriga a página externa a rolar horizontalmente, cortando tanto o geoportal quanto outros elementos da página.

## Licença

Todos os direitos reservados. Ver [LICENSE](LICENSE).
