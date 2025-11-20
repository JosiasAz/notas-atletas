# Notas Atletas

Sistema de cálculo de média de notas de atletas em competições, descartando a maior e a menor nota para garantir justiça na avaliação.

## Descrição

Este projeto implementa um sistema que calcula a média válida das notas de atletas em competições esportivas. Para evitar distorções causadas por notas muito altas ou muito baixas, o sistema descarta a maior e a menor nota de cada atleta antes de calcular a média.

## Funcionamento

O sistema processa uma lista de atletas com suas respectivas notas e, para cada atleta:

1. Ordena as notas em ordem crescente
2. Remove a menor nota (primeira posição)
3. Remove a maior nota (última posição)
4. Calcula a média das notas restantes
5. Exibe o resultado formatado

## Tecnologias

- JavaScript
- Node.js para execução

## Como Executar

1. Certifique-se de ter o Node.js instalado em sua máquina
2. Clone este repositório
3. Navegue até o diretório do projeto
4. Execute o comando:

```bash
node notas-atletas.js
```

## Exemplo de Saída

```
Atleta: Cesar Abascal
Notas Obtidas: 10,9.34,8.42,10,7.88
Média Válida: 9.253333333333334

Atleta: Fernando Puntel
Notas Obtidas: 8,10,10,7,9.33
Média Válida: 9.11

Atleta: Daiane Jelinsky
Notas Obtidas: 7,10,9.5,9.5,8
Média Válida: 9

Atleta: Bruno Castro
Notas Obtidas: 10,10,10,9,9.5
Média Válida: 9.833333333333334
```

## Estrutura do Código

- **Array de atletas**: Contém os dados de cada atleta (nome e notas)
- **Função calcularMediaAtletas()**: Processa todos os atletas e calcula suas médias válidas

## Regras de Cálculo

- Cada atleta recebe 5 notas
- A maior e a menor nota são descartadas
- A média é calculada com as 3 notas restantes
- O resultado é exibido no console

## Autor

Projeto desenvolvido como exercício de lógica de programação em JavaScript.
