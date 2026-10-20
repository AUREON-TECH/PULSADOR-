# PULSADOR

Aplicativo independente para acompanhamento do pulso operacional da captação.

## Estrutura
- `index.html`: painel responsivo.
- `app.js`: lógica do painel e importação de dados.
- `styles.css`: apresentação para celular e desktop.
- `data/resultado.json`: dados publicados do Pulsador.

## Dados
O Pulsador usa seu próprio arquivo `data/resultado.json`, sem alterar o RAIO X. Inicialmente os dados são de demonstração (valores nulos) até a fonte real ser configurada. É possível importar JSON local pelo painel. Não publicar credenciais ou dados pessoais sensíveis neste repositório público.

## GitHub Pages
Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.
