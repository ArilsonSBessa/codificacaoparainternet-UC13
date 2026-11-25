# Restaurante Sabor Caseiro — correção da página

O dono do restaurante pediu ao sobrinho uma página que "não estava saindo direito".
Esta pasta traz a versão corrigida (`index.html`) e a lista dos erros encontrados.

## Código original

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
  </head>
  <title>Restaurante Sabor Caseiro</title>
  <body>
    <h1>Sabor Caseiro
    <p>Comida mineira no fogão a lenha, de segunda a sábado.</p>
  </body>
```

## Os quatro erros

| # | Erro | Explicação | Correção |
|---|------|------------|----------|
| 1 | `<title>` fora do `<head>` | O título da aba tem que ficar dentro do `<head>`. | O `<title>` foi movido para dentro do `<head>`. |
| 2 | `<h1>` sem fechamento | Sem o `</h1>`, o navegador trata o parágrafo como parte do título. | Foi incluído o `</h1>` logo depois de "Sabor Caseiro". |
| 3 | `</html>` faltando | O documento abria com `<html>` e não fechava. | Foi incluído o `</html>` no final. |
| 4 | `<html>` sem idioma | Sem `lang`, o navegador e os leitores de tela não sabem que a página está em português. | Foi incluído o `lang="pt-BR"` no `<html>`. |

## Código corrigido

```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8">
    <title>Restaurante Sabor Caseiro</title>
  </head>
  <body>
    <h1>Sabor Caseiro</h1>
    <p>Comida mineira no fogão a lenha, de segunda a sábado.</p>
  </body>
</html>
```

## Confira

- [x] O título "Restaurante Sabor Caseiro" aparece na aba do navegador.
- [x] O `<h1>` termina logo depois de "Sabor Caseiro".
- [x] A lista dos quatro erros traz uma explicação de uma linha para cada um.
