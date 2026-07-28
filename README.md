# Contalger — Motor IBS/CBS

Pacote estático preparado para publicação no GitHub Pages.

## Arquivos

- `index.html`: aplicação completa.
- `.nojekyll`: impede o processamento do site pelo Jekyll.
- `robots.txt`: solicita aos mecanismos de busca que não indexem o protótipo.

## Como publicar

1. Crie um repositório no GitHub.
2. Envie os arquivos deste pacote para a raiz da branch `main`.
3. No repositório, abra **Settings → Pages**.
4. Em **Source**, selecione **Deploy from a branch**.
5. Selecione a branch `main`, a pasta `/(root)` e salve.
6. Aguarde o GitHub informar o endereço publicado.

Documentação oficial:  
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Observações importantes

- Não renomeie o arquivo `index.html`.
- A tabela exibe até 100 produtos por página por padrão, com opções de 50, 100 ou 200.
- Cálculos, pesquisa e exportação continuam considerando todos os produtos importados.
- Os itens importados ficam armazenados no navegador do usuário; não são enviados ao repositório.
- O `robots.txt` não protege o endereço. Se o GitHub Pages estiver público, qualquer pessoa que possuir o link poderá acessar o aplicativo.
- Não envie planilhas, cadastros ou informações de clientes para o repositório.
