# Avaliação da Efetividade de Vídeos de Adoção de Pets

## Objetivo

Somos uma ONG de animais e queremos incentivar a adoção de pets. Para isso, vamos mostrar um vídeo de animais para as pessoas. Porém, não sabemos o que é mais efetivo: um vídeo de cachorros ou um vídeo de gatos.

## Experimento

Para determinar qual vídeo é mais eficaz, realizamos um experimento com as seguintes características:

- 500 pessoas que não possuem animais de estimação participaram do experimento.
- Cada participante assistiu a um dos dois vídeos de campanha de adoção: um com gatos e outro com cachorros.
- As pessoas foram aleatoriamente divididas em dois grupos:
  - 250 pessoas assistiram ao vídeo com gatos.
  - 250 pessoas assistiram ao vídeo com cachorros.
- Após assistirem ao vídeo, perguntamos aos participantes: "Qual a chance de adotar um pet? (0-100)"

## Análise

Para avaliar se a média de probabilidade de adoção é igual entre os grupos que assistiram ao vídeo de gato e ao vídeo de cachorro, utilizamos um teste t de Student para duas amostras independentes.

### Hipóteses

- **Hipótese nula (H0)**: A média de probabilidade de adoção é igual para ambos os vídeos (gatos e cachorros).
- **Hipótese alternativa (H1)**: A média de probabilidade de adoção não é igual para ambos os vídeos (gatos e cachorros).

## Resultado
- Se o valor p (p-value) for menor que o nível de significância (α = 0.05), rejeitamos a hipótese nula e concluímos que há uma diferença significativa entre as médias das duas amostras.
- Se o valor p for maior ou igual ao nível de significância, não rejeitamos a hipótese nula e concluímos que não há evidências suficientes para dizer que as médias são diferentes.
