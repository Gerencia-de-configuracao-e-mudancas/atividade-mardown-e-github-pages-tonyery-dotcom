
# Atividade: Markdown e GitHub Pages

Este repositório contém a atividade prática sobre Markdown e GitHub Pages.

## Descrição

Exercício para aprender a criar conteúdo em Markdown e publicar uma página estática usando GitHub Pages. O repositório deve conter arquivos Markdown/HTML que representam a página do site.

## Como visualizar localmente

1. Clone o repositório:
   git clone https://github.com/Gerencia-de-configuracao-e-mudancas/atividade-mardown-e-github-pages-tonyery-dotcom.git
2. Entre na pasta do projeto:
   cd atividade-mardown-e-github-pages-tonyery-dotcom
3. Abra o arquivo index.html no navegador ou sirva localmente com um servidor simples:
   python -m http.server 8000
   e acesse http://localhost:8000

## Como publicar com GitHub Pages

1. No repositório, vá em Settings → Pages.
2. Em "Source", selecione o branch `main` e o diretório (`/` root ou `/docs`) conforme onde esteja sua página.
3. Salve. A URL ficará semelhante a:
   https://<usuario-ou-organizacao>.github.io/<nome-do-repo>

Observação: se preferir usar um branch separado (ex: gh-pages), crie o branch e publique a partir dele.

## Estrutura sugerida

- index.html ou README.md (página principal)
- assets/ (imagens, css, js)
- docs/ (opcional - se usar GitHub Pages a partir de /docs)

## Como contribuir

1. Faça um fork do repositório.
2. Crie uma branch com sua alteração:
   git checkout -b minha-mudanca
3. Faça commits das suas alterações:
   git add .
   git commit -m "Minha contribuição"
4. Envie para sua fork e abra um pull request.

## Licença

Este projeto pode usar a licença MIT — adapte conforme necessário.

## Autor

Tony Ery (tonyery-dotcom)
