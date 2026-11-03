# Hugo Mathos · cartão digital

Cartão de visita digital do Hugo Mathos, da Mathos Contabilidade. Publicado em https://hugo-mathos.vercel.app.

Site estático, sem build. Os arquivos:

- `index.html`: página completa, com a abertura animada (caduceu → M da Mathos), serviços, formulário pro WhatsApp e QR code
- `hugo.webp`: foto recortada
- `og.jpg`: imagem de prévia do link (WhatsApp, Instagram)
- `favicon.svg`: ícone da aba

Contatos, horário e mensagem do WhatsApp ficam no objeto `CONTATO`, no começo do `<script>` em `index.html`.

## Link da bio do Instagram

`links/index.html` é a página do link da bio do @mathoscontabilidade, servida em `/links`. O `vercel.json` faz o domínio `links.mathoscontabilidade.com.br` abrir essa página direto. Os dados ficam no objeto `CONTATO` dela.
