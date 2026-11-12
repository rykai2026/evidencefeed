EvidenceFeed v6.3 — IndexedDB

Substitua os arquivos da raiz do repositório GitHub por estes arquivos.
Não é necessária pasta articles/.

Mudança principal:
- artigos, imagens e PDFs incorporados são salvos no IndexedDB;
- localStorage guarda somente o ID do artigo ativo;
- evita o erro "exceeded the quota" da v6.2;
- mantém importação manual de .efarticle;
- Original abre o PDF incorporado no pacote;
- migra artigos pequenos existentes da v6.1/v6.2 quando possível.
