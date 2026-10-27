EvidenceFeed v5.6 — correção definitiva das imagens
As figuras do Abedin usadas nos Reels estão incorporadas diretamente no index.html.
O renderizador reconhece tanto artigos antigos com caminhos figure-X.png quanto artigos novos com data:image.
Isso evita depender de assets, cache ou localStorage para as imagens.
