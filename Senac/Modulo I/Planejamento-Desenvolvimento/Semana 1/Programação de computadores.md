# Introdução

> Programação de computadores nada mais é do que projetar, desenvolver e construir um programa executável em um computador, para que o mesmo cumpra uma determinada tarefa ou responda com determinado e/ou específico resultado.

# Código

> As primeiras linguagens de programação se baseavam em instruções descritas com sequências de bytes, ou seja, eram instruções binárias. Um exemplo de instrução seria a seguinte sequência de bytes:

```
01000011 00111010 00111011 01000001 00101011 01000100
```

Observe que pode ser bastante complexo compreender o que cada sequência de 0s e 1s significa no programa. O programador deveria ter profundo conhecimento de quais componentes do dispositivo está manipulando, o que tornava a programação trabalhosa. Assim, surgiram linguagens mais compreensíveis ao ser humano com a criação das linguagens montadoras, ou Assembly. As instruções recebiam nomes, também denominados mnemônicos, que ficam mais compreensíveis. A instrução a seguir, por exemplo, soma dois valores – um armazenado em um registrador (memória) de endereço “CL” e outro valor no registrador “BH”.

```asembly
ADD CL,BH
```

Isso seria correspondente em binário à sequência 00000010 11001111.

Códigos de linguagens montadoras são interpretados por um compilador, que cria as instruções binárias nescessárias para que o computador se comporte da maneira desejada pelo programador

# Linguagens de alto nível

> As linguagens de alto nível, assim, escondem instruções mais básicas da computação em instruções mais sucintas. Assim, uma instrução acaba sendo capaz de executar várias operações de uma vez.

# Compiladores

Compiladores e interpretadores, normalmente, convertem o código de uma linguagem de alto nível para uma linguagem que o computador possa enteder. Em geral os compiladores convervem o código para Asembly para que então seja interpretado pela CPU como um binário
![](https://learn-us-east-1-prod-fleet02-xythos.content.blackboardcdn.com/638e5f8fa10ff/33945158?X-Blackboard-S3-Bucket=learn-us-east-1-prod-fleet01-xythos&X-Blackboard-Expiration=1676473200000&X-Blackboard-Signature=9IOF733M1T8tSr6H28T6n3kK1VVHXI27h9CBYZkhehs%3D&X-Blackboard-Client-Id=306527&X-Blackboard-S3-Region=us-east-1&response-cache-control=private%2C%20max-age%3D21600&response-content-disposition=inline%3B%20filename%2A%3DUTF-8%27%27esquema01.png&response-content-type=image%2Fpng&X-Amz-Security-Token=IQoJb3JpZ2luX2VjEJL%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJHMEUCIQCbQrDpJYArfieyVBpqZSYlUylqWa7WUaE3REqR23dGBQIgDlr2qZqJdH3EOUqzLJ4Qa2yWmcb7fc5AldRFPZ4DUvYqzAQIKxACGgw2MzU1Njc5MjQxODMiDMzGfnvfz9H7pW%2BiYiqpBJpL%2B3kDTLHQQAib41uL0MCS%2B2J%2Bx8ium5SaTRa6YDptyfHDpS%2FZle3Iplba9AAOfIJS9s6yk94xUDtOZgmh3BUQTfbPXj8idNb7Qzxqi0NRHrL8J3vMR32Y2%2B52bPiv3RuVWFIUuh%2FIwSrVVsnVRt%2BFW40nHD9R1ztZGeHdkAg1M%2BGywgJK%2FL%2BBk5y3QZpQKVGzfj2cET%2BfieaFpkPcctwJKIdcnLaEymJ6sDPaYzkZyqEvxC8uqS3uI4NPY0Ts4PBSAoOxfCrDotL6GBZ5EDsTTqk9VjjT1aTxN8xTnDYTeCkKATx83u5hffjA8kTvgkpKBdJx1yRkEDscyZ0QpkDB%2FWXeQlRAZEy7UUBtW2Qe%2FiaYDoAMwuk2eH30QavmG3CAuOyvBBrNc2YTQpT%2BNjFjpCQgkJ3SoqL51Wbd5T2TKqWmJDyk1dLwX7mdpfaadxLVO10BUexZNsAm%2BEcuM0gOrC5UwAVqsD%2Bl%2BeXiSSl6MGZpnbGttO1RPPuH6OF5MiAlluk45mzrI0yzpVCG%2BI5%2FTWGmAS3o7UjwiXkt5NwQGXb99T2x0FNqEs2037bpB2T3zQxsTYUZJT5ZBiP68pvxmDYwF5fGiH6wcL7okWM8inY%2FRKATUPsugGujxwRZ7rKSGg1qJVjGOAa6BMTmjFAH0by4ivCYq5UQvl%2Bzdn1td%2BRp437dfjbmW7LGsOQhljeOEdqKWvqpA8XSW3v9wQ2ple767t%2BcFjUw%2BNKynwY6qQGAErnuUnFDhHtZ9NE04fvg4pz%2BOV6mXAvhsoravx1HZvNKrswJxcr425%2FwggaZjcq49Cd%2FtxAurNNZ13BRSfSvK%2FRZ6HaocJJ6CcEatFnolwSnDMq8RTGHh5YciM1hD%2Fof7ABIIUmZnzf4eeO5Jz53S7M90w62Kr44QVu5lB2nf%2Fcl0rNVGfR6RJTYFjVtjKBLymG3hBpsnZeHRp59Bt6FU%2BSpcjvIQAml&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20230215T090000Z&X-Amz-SignedHeaders=host&X-Amz-Expires=21600&X-Amz-Credential=ASIAZH6WM4PLZB5GNPW7%2F20230215%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=83d0dd36646e5fd5cb7e812e99d5317e7b4a3d80d80a6529bcaf036ee69273b5)

# Logica proposicional

> A lógica proposicional se baseia no conceito de proposições, uma sentença declarativa (expressa por palavras ou símbolos) cujo valor pode ser considerado verdadeiro ou falso (e nenhum outro diferente desses).

Dessa forma a lógica proposicional liga-se a ciência da computação na medida em que ela assume valores binário (verdadeiro e falso) assim como os circuitos de um computador estão apenas ligados ou desligados (1 e 0).

Na lógica proposicional sentenças são ligadas por conectivos "e" e "ou", formando conjuntos de proposições que podem ser verdadeiras ou falsas.

Três princípios são importantes nas proposições:

- Uma proposição verdadeira é verdadeira; uma proposição falsa é falsa (princípio da identidade).
- Nenhuma proposição poderá ser verdadeira e falsa ao mesmo tempo. (princípio da não contradição).
- Uma proposição ou será verdadeira, ou será falsa: não há outra possibilidade (princípio do terceiro excluído).

Considere as proposições:

- **q**: João é medico
- **r**: Larissa foi ao cinema ontem
- **p**: 5 > 8

Podemos juntar essas proposições através dos conectivos para formar conjuntos de verdade:

- Conjunções: formadas pelo conectivo E, só são verdadeiras caso ambas as partes da sentença sejam verdadeiras:
  - q^r: "João é médico E Larissa foi ao cinema ontem" - Verdadeiro
  - q^p: "João é médico E 5 > 8" - Falso
- Disjunções: São formadas pelo conectivo OU, só são falsas caso ambas as proposições sejam falsas, considere que q é verdadeiro, r e p são falsos:
  - q∨p: "João é medico ou 5>8" - Verdadeiro
  - r∨p: "Larissa foi ao cinema ontem ou 5>8" - Falso

Há ainda dois outros operadores na lógica proposicional:

- “Se então” (→) o p → q (se p então q) será falso apenas se q for falso
- “Se e somente se” (↔) o p ↔ q (p se e somente se q) será verdadeiro quando p e q forem ambos verdadeiros ou ambos falsos.
