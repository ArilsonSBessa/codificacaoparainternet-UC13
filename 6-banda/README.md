# Banda Os Decibéis — testando no DevTools

Página da banda com a agenda de três shows: data, cidade e local, um show por parágrafo.

## Como fazer o teste

1. Abra o `index.html` no navegador.
2. Aperte **F12** e vá na aba **Elements**.
3. Na árvore, ache o `<h1>Os Decibéis</h1>` e dê dois cliques no texto.
4. Troque o nome (por exemplo, para "Os Barulhentos") e aperte **Enter**. A tela muda na hora.
5. Aperte **F5**. O nome original volta.
6. Abra o `index.html` no VS Code. O arquivo continua com "Os Decibéis".

## Por quê?

O DevTools altera só a cópia da página carregada na memória do navegador. Quando você aperta F5, o navegador pede o arquivo de novo e recebe o `index.html` original, que nunca foi alterado.
