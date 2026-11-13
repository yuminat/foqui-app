# Foqui · protótipo do app

Protótipo navegável e responsivo do app institucional da Foqui Sanduíches (HTML, CSS e JavaScript, sem dependências).

## Como publicar no GitHub Pages
1. Crie um repositório e envie `index.html`, o arquivo `.nojekyll` e a pasta `FOTOS/` (com as subpastas). Mantenha os nomes das pastas em maiúsculas.
2. Em **Settings > Pages**, escolha a branch `main` e a pasta `/ (root)`.
3. Abra o endereço que o GitHub mostrar.

## Fotos
Já estão na pasta as fotos dos produtos do cardápio (redimensionadas para web). Ainda faltam, e o app mostra uma ilustração no lugar: `mignon`, `rabanada-brulee`, `chantilly`, `queijo-mucarela`, `bacon`; a fachada e a capa do Running Club já estão em `FOTOS/SOBRE/`. As capas `FOTOS/VIDEOS/reel-1..3.jpg` são provisórias; troque pelas capas reais dos Reels.

- Produtos: `FOTOS/nome-do-produto.jpg`
- Sobre (donos e fachada): `FOTOS/SOBRE/`
- Capas dos vídeos: `FOTOS/VIDEOS/`

A tabela de nomes está em `FOTOS/LEIA-ME.txt`.

## Vídeos do Instagram
Os 5 links já estão em `const REELS` no `index.html`. Para trocar o nome de cada vídeo, edite `titulo`; as capas ficam em `FOTOS/VIDEOS/reel-1.jpg` a `reel-5.jpg` (hoje são fotos provisórias). O vídeo toca dentro do app.

## Link da Goomer
No `index.html`, procure `GOOMER_URL` e cole o link do cardápio digital da Foqui.

## Responsividade
No celular o app ocupa a tela inteira; em tablet e computador aparece centralizado em moldura. Acompanha o modo claro e escuro do aparelho.

## Jogo
O jogo "Foqui: Fugir do óbvio" está em `JOGO/index.html` e abre em tela cheia pela aba Jogar (exige login). No celular em pé, o app gira o jogo para ficar na horizontal. Ao fim do turno, a pontuação vira pontos de fidelidade (1 ponto a cada 20, até 50 por dia) e o jogo mostra quantos pontos entraram na conta. Para mudar a regra, edite a função `termina()` em `JOGO/index.html` (linha com `Math.floor(Jogo.pontos/20)`) e o limite diário `DAILY` no `index.html`.
