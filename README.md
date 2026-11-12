# CJ Notícia 24H — Central de Notícias

Primeira versão de interface para alojar no GitHub Pages.

## O que já funciona
- Painel responsivo para telemóvel e computador
- Criar, editar e apagar rascunhos
- Categorias, resumo, texto, imagem, legenda, fontes e etiquetas
- Fila de publicação e histórico local
- Guardar dados no armazenamento local do navegador

## Limitações importantes desta versão
- Ainda NÃO publica no Blogger.
- Os dados ficam guardados apenas no navegador/dispositivo em que foram criados.
- Agendamento é apenas um campo de data nesta versão, não um serviço automático.
- A integração Blogger requer configurar OAuth 2.0 e a Blogger API com autorização da conta Google. Não colocar segredos ou tokens num site público.

## Publicar no GitHub Pages
1. No GitHub, crie um repositório público chamado `cjnoticia24h`.
2. Carregue o ficheiro `index.html` para a raiz do repositório.
3. Abra Settings > Pages.
4. Em Build and deployment, escolha Deploy from a branch.
5. Selecione `main` e `/ (root)`, depois Save.
6. Aguarde a publicação; o GitHub mostrará o endereço do site em Settings > Pages.

Depois será necessário configurar a integração segura com o Blogger antes de ativar o botão Publicar.
