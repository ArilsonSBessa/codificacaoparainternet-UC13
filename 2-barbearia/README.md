# Barbearia Navalha de Ouro — acentos e cedilha

Página com os serviços da barbearia, salva em **UTF-8**.

## Conteúdo

- `<title>`: Barbearia Navalha de Ouro — Cortes e barba
- `<h1>`: Navalha de Ouro
- Três parágrafos:
  - Corte tradicional — R$ 35,00
  - Barba com toalha quente — R$ 30,00
  - Promoção: corte + barba às terças-feiras

## Confira

- [x] O `<meta charset="UTF-8" />` está no `<head>`.
- [x] O travessão (—), o cifrão (R$), a vírgula, o "ç" e o "é" aparecem certos.
- [x] A barra inferior do VS Code mostra **UTF-8**.

## Por que o UTF-8 importa?

O `<meta charset="UTF-8">` diz ao navegador como ler os caracteres do arquivo. Se o arquivo não estiver salvo em UTF-8, ou se o charset estiver faltando ou errado, os acentos viram símbolos estranhos, como `PromoÃ§Ã£o` no lugar de `Promoção`.
