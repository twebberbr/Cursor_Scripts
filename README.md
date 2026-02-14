# Cursor_Scripts

## Krigagem ordinaria - multiplicador de Lagrange (didatico)

Arquivo principal:

- `krigagem_lagrange_didatico.html`

Como usar:

1. Abra o arquivo HTML direto no navegador.
2. Ajuste os pontos amostrais (`x` e `z`), o ponto alvo (`x0`) e os parametros (`sigma2`, `a`).
3. Observe os 4 passos:
   - montagem de `C` e `c0`;
   - montagem do sistema aumentado com `lambda`;
   - solucao dos pesos;
   - comparacao entre sistema com restricao e sem restricao.

Objetivo didatico:

- mostrar claramente que `lambda` aparece para impor `sum(w_i) = 1`;
- comparar com a solucao sem restricao (`Cw = c0`) para ver a diferenca na soma dos pesos.
