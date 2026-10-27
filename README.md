# Funcional Conciliação — canal público de atualizações

Este repositório público possui somente **metadados de versão** e, a partir da versão 2.9.6,
poderá hospedar o executável Windows em **GitHub Releases**, para permitir atualização
sem exigir conta GitHub dos usuários.

O código-fonte, a compilação, os testes e os relatórios contábeis de clientes ficam
exclusivamente no repositório **privado** `guiilhermetluz-max/funcional-conciliacao-clientes`.

**Nunca publicar aqui:** planilhas `.xls`, `.xlsx`, dados reais, razão, CT-e,
logs de clientes, capturas contendo informações contábeis, tokens, senhas,
chaves privadas, código-fonte ou artefatos que contenham dados reais.

O `latest.json` inclui `product`, `version`, `published_at`, `notes`,
`download_url`, `sha256` e `size_bytes`. Somente após um executável
ser publicado e validado seu hash e tamanho, o GitHub Actions do repositório
privado pode atualizar este manifesto.

**Aviso:** um executável público pode ser analisado por terceiros. Não inserir
segredos nem dados contábeis de clientes no build. A publicação pública do
executável depende da configuração segura do segredo `PUBLIC_UPDATES_TOKEN`
no repositório privado. Até isso ocorrer, o manifesto não deve anunciar
uma versão sem download público válido.
