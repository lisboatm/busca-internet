# README - Problema do Clique em Links

## Descrição do Problema

João fez uma pesquisa em seu site de busca favorito e encontrou a resposta que estava procurando no terceiro link listado. Ele notou que `t` pessoas já haviam clicado nesse link. Além disso, ele leu que o número de pessoas que clicam no segundo link é o dobro do número de pessoas que clicam no terceiro link. Da mesma forma, o número de pessoas que clicam no segundo link é a metade do número de pessoas que clicam no primeiro link. 

João quer descobrir quantas pessoas clicaram no primeiro link da busca.

## Objetivo

O objetivo deste problema é determinar quantas pessoas clicaram no primeiro link, dado o número de pessoas que clicaram no terceiro link.

## Lógica do Problema

Para resolver este problema, devemos estabelecer relações entre os números de pessoas que clicam nos links:

1. **Terceiro link**: \( t \) (número de pessoas que clicaram)
2. **Segundo link**: \( 2t \) (o dobro do terceiro link)
3. **Primeiro link**: \( 4t \) (o dobro do segundo link, que é \( 2t \))

Com isso, podemos determinar que o número de pessoas que clicaram no primeiro link é \( 4t \).

## Entrada

- A entrada consiste em um único inteiro \( t \) que representa o número de pessoas que clicaram no terceiro link da busca.
- Restrições: \( 1 \leq t \leq 1000 \)

## Saída

- Para cada caso de teste, imprima uma única linha contendo um inteiro que indica quantas pessoas clicaram no primeiro link.

## Exemplo de Entrada e Saída

### Exemplo 1

**Entrada**
```
5
```

**Saída**
```
20
```

### Exemplo 2

**Entrada**
```
1
```

**Saída**
```
4
```

### Exemplo 3

**Entrada**
```
10
```

**Saída**
```
40
```

## Implementação

A implementação deve seguir a lógica descrita acima. Aqui está um exemplo de código em Python que resolve o problema:

```python
# Lê o número de pessoas que clicaram no terceiro link
t = int(input())

# Calcula o número de pessoas que clicaram no primeiro link
primeiro_link = 4 * t

# Exibe o resultado
print(primeiro_link)
```

## Considerações Finais

- Este problema é um exemplo simples de raciocínio lógico e manipulação de números inteiros.
- Certifique-se de testar o código com diferentes valores de entrada para garantir que a solução está correta.
