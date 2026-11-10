# Nautasensores

Traduções para o português dos guias técnicos da Actisense, publicadas pelo GitHub Pages.

## Estrutura

```
index.html          página inicial com todos os documentos
documentos.js       lista de documentos exibida na página inicial
rede-hibrida-nmea-0183-nmea-2000/
  index.html        o documento traduzido, com as imagens embutidas
  capa_linkedin.jpg
  miniatura.jpg     imagem do cartão na página inicial
```

Cada documento tem a sua pasta, sempre com um `index.html`. Assim o link fica curto, por exemplo `.../nautasensores/rede-hibrida-nmea-0183-nmea-2000/`.

## Como publicar uma nova tradução

1. Crie uma pasta para o documento, com nome em minúsculas e sem acentos, e coloque nela o `index.html` traduzido e uma `miniatura.jpg`.
2. Em `documentos.js`, copie o bloco de um documento existente e ajuste título, resumo, data, caminho, imagem e link do original.
3. Faça o commit. Em um ou dois minutos a página inicial já mostra o novo documento.

## Pré-visualização no LinkedIn

O LinkedIn só mostra a imagem de capa quando a tag `og:image` do documento tem o endereço completo. No `index.html` de cada documento, troque

```html
<meta property="og:image" content="capa_linkedin.jpg">
```

pelo endereço completo da imagem, por exemplo

```html
<meta property="og:image" content="https://agrosensores.github.io/nautasensores/rede-hibrida-nmea-0183-nmea-2000/capa_linkedin.jpg">
```

Depois cole o link do documento no [Post Inspector](https://www.linkedin.com/post-inspector/) para o LinkedIn atualizar a pré-visualização.

## Direitos

Os textos e imagens originais pertencem à Actisense. Cada documento traz o link para a versão original.
