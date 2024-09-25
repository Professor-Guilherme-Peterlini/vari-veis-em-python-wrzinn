# Exercícios Detalhados: Variáveis em Python

## Exercícios Práticos

1. **Escopo de Variáveis**
   Crie um programa que demonstre a diferença entre variáveis locais e globais. Defina uma variável global, crie uma função que tente modificar essa variável global (sem usar a palavra-chave `global`), e outra função que a modifique corretamente usando `global`. Imprima o valor da variável após chamar ambas as funções.

2. **Mutabilidade vs. Imutabilidade**
   Crie uma lista e uma string. Tente modificar um elemento da lista e um caractere da string. Use a função `id()` para mostrar como o ID da lista permanece o mesmo após a modificação, enquanto o ID da string muda quando você tenta "modificá-la".

3. **Tipagem Dinâmica**
   Escreva um programa que demonstre a tipagem dinâmica do Python. Crie uma variável e atribua a ela valores de diferentes tipos (int, float, string, lista) em sequência. Use a função `type()` para imprimir o tipo da variável após cada atribuição.

4. **Gerenciamento de Memória**
   Crie duas variáveis que referenciam a mesma lista. Modifique a lista através de uma das variáveis e mostre que a mudança é refletida na outra. Em seguida, use o módulo `copy` para criar uma cópia superficial e uma cópia profunda da lista, e demonstre a diferença entre elas ao modificar elementos aninhados.

5. **Conversão de Tipos e Operações**
   Crie um programa que solicite ao usuário para inserir dois números como strings. Converta-os para float, realize algumas operações matemáticas (adição, subtração, multiplicação, divisão), e então converta os resultados de volta para strings para exibição. Lide com possíveis erros de conversão.

## Exercícios Teóricos

1. **Explique o conceito de tipagem dinâmica em Python. Como isso difere de linguagens com tipagem estática? Quais são as vantagens e desvantagens da tipagem dinâmica?**

   Resposta esperada:
   - Definição de tipagem dinâmica
   - Comparação com tipagem estática
   - Vantagens: flexibilidade, menos código verboso
   - Desvantagens: potenciais erros de tipo em tempo de execução, possível impacto no desempenho

2. **Descreva a diferença entre objetos mutáveis e imutáveis em Python. Dê exemplos de cada um e explique como isso afeta o comportamento das variáveis que referenciam esses objetos.**

   Resposta esperada:
   - Definição de mutabilidade e imutabilidade
   - Exemplos: listas (mutáveis) vs. tuplas (imutáveis)
   - Explicação de como a mutabilidade afeta operações e atribuições
   - Discussão sobre como isso se relaciona com o conceito de identidade de objetos (função `id()`)

3. **Explique o conceito de escopo de variáveis em Python. Como o Python lida com variáveis locais e globais? O que é a regra LEGB e como ela se aplica à resolução de nomes de variáveis?**

   Resposta esperada:
   - Definição de escopo local e global
   - Explicação da palavra-chave `global`
   - Descrição da regra LEGB (Local, Enclosing, Global, Built-in)
   - Exemplos de como Python resolve nomes de variáveis em diferentes contextos

Instruções para os exercícios:

- Para os exercícios práticos, escreva o código Python completo para cada problema.
- Para os exercícios teóricos, forneça explicações detalhadas, use exemplos quando apropriado, e considere tanto os aspectos técnicos quanto as implicações práticas de cada conceito.
- Teste seu código dos exercícios práticos com diferentes entradas para garantir que ele funcione corretamente em vários cenários.
