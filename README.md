# PROG2.TRI2.ATIV3

# PROG2.TRI2.ATIV3 - Lista de Atividades

## Objetivo

O objetivo desta atividade é compreender a motivação e a utilidade dos principais conceitos da Programação Orientada a Objetos em TypeScript.

Em cada questão, você deverá produzir um pequeno trecho de código que demonstre claramente a necessidade do conceito solicitado. Sempre que considerar apropriado, compare sua solução com uma abordagem procedural ou funcional para justificar por que o recurso de orientação a objetos torna a solução "superior" am algum aspécto.

## Instruções Gerais

Todas as atividades devem ser desenvolvidas utilizando o TypeScript Playground.

Para cada atividade:

1. Copie o enunciado da atividade para o README.md do repositório.
2. Resolva a atividade no TypeScript Playground.
3. No topo do arquivo, adicione um comentário explicando:
   * qual problema está sendo resolvido;
   * qual conceito de orientação a objetos está sendo demonstrado;
   * por que esse conceito é útil;
   * quais dificuldades surgiriam sem sua utilização;
   * se aplicável, compare a solução com uma abordagem procedural ou funcional.
4. Gere o link compartilhável do Playground.
5. Cole o link da resposta imediatamente abaixo do enunciado correspondente no README.md.

O repositório deve possuir o nome:

**PROG2.TRI2.ATIV3**

## Enunciado

Escreva trechos de códigos que justiquem a necessidade da existencia dos temas abaixo em a objetos, se necessário compare com programçaõ funcional para justificativa, adicione ao topo de seus arquivos comentários que justifiquem a abordagem tomada na solução (para cada tópico faça duas soluções diferentes):

1. Classes e objetos
   [exemplo 1](https://www.typescriptlang.org/pt/play/?#code/PTCKFcEMDsBMHsAEsCmAzAltJ4C2lEBjAG0gGcyVEVwiAnDHfasgBxUIytUV3mJ4BHcFQBukDIkp1E4YgBcMxDAC9ICRK0h0CBQg0gBzgMdIe2UfDKJ4AIwBWKeVYA0icmQy43aSJ2XyMBoEZFCIdDQKSqpGpm7QplIocEisEZxkSChk+iiiKHQAUCAWkLjJ8lRW7vIMtuDO1lTlzgjWGnaOzm6Q7NDkNXXgGDJ4iOLE8HQAdIWFJB6IAArZmZAA3oWI24jY5QBcZLVYAOZbO4Tw0Ed04ITOdAAUeyiHx9AnAJSbO7+I8gALDBkaYvRAAXl28HK522AF9YYhfKQnmgdJQ3gwPt9Eb8IvJwHRoEj0ShEQiEcQnIgMIU0FNHhhwQBGADcNIAPMyAAzc9kYADUApxv0u13kmlW8AIkOgKAA7sspZBHgAifCAmhkVWfRC4i5XTJU6aTE6PAAGABJ1uwKNLQdCUHDkMCMYhrba1tNkdo1YRIIFWFhbOQdXDzZ9CgigA)
   [exemplo 2](https://www.typescriptlang.org/play/?#code/PTCKFcEMDsBMHsAE4DOSDGAbSKUFMVE9xEAHeXJPAD1JlgEsAnIxB6UzPAWz2gBdILbpAaEAZuGgBzyElh5EI6HmZJSTSPwbpIAGkQArSIgCO4Rf3iwciWxvgaGeGwsKLeVhIQSJ4AI0M8K0QAN1EiFEEWHmRuZGgdJEx4XUwDcUh0BkwGQTgkFCgAKBAUtIYAL0hZKnjeBiRbdD5+PlsFRFzoAAsTc0V8KTImeABzTREya0s8FmgkSX5wUYA6RGLirBxCAAUCNEgAb2LEM8QF3gAuKKZ2MdPzhlc8K+hwbn85x7P0eGhbuB0FYmAAKS6vW73AzPSAKN4fL5MACUJ3O6MQ-B6YlWEMQAF4LvBeD8MVicbDOoTKXhSQBfUmZbBg8SafA3fh3aBjVGk9FMYIraCIVk4WnohkMrj8NjFcTwMEMfEARgA3GwADzKgAM2vVDAA1Abeei-gCZaQDvATISVAB3RD7SiQUEAIhEWOIKFdemVABZkRsMeczWguKsUmNQQADAAkR0tztxxLwdNB8cTh1WNLpdgWKEDjFwr0QGatkFWTKEbt0k388Gw3uRdOjyOKDKAA)
0. Atributos e métodos [exemplo 1](https://www.typescriptlang.org/play/?#code/PTCKFcEMDsBMHsAE4DOSDGAbSKUFMVE9xEAHeXJPAD1JlgEsAnIxB6UzPAWz2gBdILbpAaEAZuGgBzyElh5EI6HmZJSTSPwbpIAGkQArSIgCO4Rf3iwciWxvgaGeGwsKLeVhIQSJ4AI0M8K0QAN1EiFEEWHmRuZGgdJEx4XUwDcUh0BkwGQTgkFCgAKBAUtIYAL0hZKnjeBiRbdD5+PlsFRFzoAAsTc0V8KTImeABzTREya0s8FmgkSX5wUYA6RGLirBxCAGFc1rwAb2LEM8QF3gAuKKZ2MdPzhlc8K+hwbn85x7OeUUwbvw7tAHudEEw+DY3h8vkwfoh0PBoLdwOgrEwABSXV63e4GZ6QBTQz5zPQQuCQYmwvR-HKA4FjACUJzBYP4PTEq2xiAAvBd4Lx4WyOShVgTOnzxXghed2ZzaZheUQRDkZWc5aLyTYlVrIPCAL7wxHcDRCDEOWDgKz0vEjPCIqlzZlqrrBDZgw2Grj8NjFcTwTEMHkARgA3GwADzBgAM0fDDAA1AnnWDEcifaQCGgTHyVAB3RD7ZwCPAYgBEInZxBQZb0wYALHXVrHo3oK1oetWAAJjFWYVbGsuM92ss5ptBcVYpMYYgAGABIjpnKJAuQK8PqMYvl9mxS99XYFihh4xcK9ENus-BV8bTZiy7pJv54NgawYY9HGfrZ4zioagA)
0. Construtores (constructor)
0. Instanciação de objetos
0. Modificadores de acesso (public, private, protected)
0. Propriedades somente leitura (readonly)
0. Métodos estáticos (static)
0. Propriedades estáticas (static)
0. Encapsulamento
0. Herança
0. Polimorfismo
0. Abstração
0. Getters e setters
0. Classes abstratas (abstract)
0. Métodos abstratos
0. Sobrescrita de métodos (override)
0. Sobrecarga de métodos (method overloading)
0. Parâmetros opcionais em métodos
0. Parâmetros padrão
0. Herança simples
0. Cadeia de herança
0. Tratamento de exceções (throw, try, catch)
0. Classes e herança de classes de erro
