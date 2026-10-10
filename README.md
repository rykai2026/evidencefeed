# EvidenceFeed MVP

Primeiro protótipo funcional do app pessoal de resumos visuais de artigos.

Incluído:
- Feed mobile
- Os três formatos no mesmo artigo: 30 sec EN, 3 min EN, 10 min PT
- Busca (interface)
- Adicionar por foto, PDF, DOI/PMID (interface)
- Fluxo de identificação por foto
- Salvos (interface)
- PWA instalável

Importante: esta versão é o front-end/MVP. A busca real na web e a geração automática por IA precisam de um backend/API para evitar expor chaves no celular.

Para testar no computador:
python -m http.server 8000
e abra http://localhost:8000/evidencefeed_mvp/

No celular, hospede a pasta em um serviço estático HTTPS ou rode na rede local.
