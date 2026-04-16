A secrete aparece como "***" pois são mascaradas automaticamente por segurança e as variáveis não são mascaradas pois não são consideradas informações sensíveis.

O job deploy_app não consegue ler BUILD_VERSION pois as variáveis que foram criadas através de $GITHUB_ENV estão limitadas ao escopo do job que foram criadas.
