# Project Gutenberg Bulk Downloader - Part 5

Continuação da coleção TXT individual do Project Gutenberg.

Este repositório inicia após o checkpoint confirmado do repositório 4, Gutenberg ID 2364.

Fonte de catálogo:
https://www.gutenberg.org/cache/epub/feeds/pg_catalog.csv.gz

TXT preferencial:
https://www.gutenberg.org/cache/epub/<ID>/pg<ID>.txt

Fallbacks:
- https://www.gutenberg.org/files/<ID>/<ID>-0.txt
- https://www.gutenberg.org/files/<ID>/<ID>.txt

Arquivos de controle:
- `txt-continuation-state.json`
- `txt-direct-index.tsv`
- `books_txt/`

A execução é feita por GitHub Actions em lotes, com SHA-256 e checkpoint por Gutenberg ID.
