EvidenceFeed v5.1
Atualização: importação automática por deep link.
Exemplo:
https://rykai2026.github.io/evidencefeed/?article=abedin-2021-wide-qrs-v5

Ao abrir o link, o app:
1. busca /articles/<artigo>.json;
2. salva/atualiza o artigo no armazenamento local;
3. torna o artigo ativo;
4. remove ?article= da barra de endereço;
5. mostra imediatamente Feed, Questions, Review e Article.

O pacote inclui Peran 2020 e Abedin 2021.
Faça upload de TODO o conteúdo para a raiz do repositório, preservando /articles/.
