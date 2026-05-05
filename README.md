```

---

> "A programação é a melhor alquimia da mente humana. Transforma pensamentos em realidade." — *Alan Turing*Aqui está uma proposta de `README.md` profissional e estruturada para o seu repositório no GitHub, baseada nos 35 exercícios de lógica e algoritmos[cite: 5].

---

# 💻 Lógica de Programação com Portugol Studio

Este repositório contém uma coleção de **35 exercícios práticos** desenvolvidos para o aprendizado de lógica de programação, algoritmos e estruturas de controle utilizando o **Portugol Studio**.

O conteúdo é baseado na lista de atividades da **Profa. Luana Leal**[cite: 5].

## 📋 Sobre o Projeto

O objetivo deste projeto é desenvolver o raciocínio lógico através da escrita, correção e interpretação de códigos. Os exercícios abrangem desde comandos sequenciais simples até desafios integradores como jogos e calculadoras[cite: 5].

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Portugol (Pseudocódigo)
*   **Ferramenta:** [Portugol Studio](http://univali.br/portugolstudio)

## 📚 Estrutura dos Exercícios

Os exercícios estão divididos em seis módulos progressivos[cite: 5]:

1.  **Algoritmos e Estrutura Sequencial:** Comandos de saída (`escreva`), quebras de linha e sintaxe básica[cite: 5].
2.  **Dados e Variáveis:** Declaração de tipos (`inteiro`, `real`, `cadeia`, `caracter`, `logico`), constantes e expressões matemáticas[cite: 5].
3.  **Entrada, Saída e Atribuição:** Interação com o usuário através do comando `leia` e manipulação de variáveis[cite: 5].
4.  **Estruturas Seletivas:** Condicionais simples e compostas (`se...senao`) e estruturas de múltipla escolha (`escolha...caso`)[cite: 5].
5.  **Estruturas Repetitivas:** Laços de repetição `enquanto`, `para` e `faca...enquanto`[cite: 5].
6.  **Desafios Integradores:** Projetos que unem diversos conceitos, como:
    *   Gerador de Tabuada[cite: 5].
    *   Calculadora Funcional[cite: 5].
    *   Cálculo de Fatorial[cite: 5].
    *   Jogo de Adivinhação de Números[cite: 5].

## 🚀 Como Executar

1.  Faça o download e instale o **Portugol Studio**.
2.  Clone este repositório:
    ```bash
    git clone [https://github.com/seu-usuario/nome-do-repositorio.git](https://github.com/seu-usuario/nome-do-repositorio.git)
    ```
3.  Abra o Portugol Studio.
4.  Vá em `Arquivo > Abrir` e selecione o exercício desejado (arquivo `.por`).
5.  Pressione **F9** para executar o programa.

## 📝 Exemplo de Código (Exercício 33 - Calculadora)
```portugol
// Exemplo de estrutura utilizada nos desafios integradores
escolha (opcao) {
  caso 1: 
    escreva("Resultado da Soma: ", num1 + num2)
    pare
  caso 2: 
    escreva("Resultado da Subtração: ", num1 - num2)
    pare
  // ... outros casos
}
```

---

> "A programação é a melhor alquimia da mente humana. Transforma pensamentos em realidade." — *Alan Turing*[cite: 5]
>
> Aqui está a lista completa das questões extraídas da sua atividade prática, prontas para serem adicionadas ao seu repositório[cite: 5]:

## 📝 Lista de Exercícios - Portugol Studio

### 1. Algoritmos e Estrutura Sequencial
1. Escreva um algoritmo que utilize apenas comandos `escreva` para desenhar a letra inicial do seu nome usando asteriscos (*) na tela[cite: 5].
2. Corrija o erro de sintaxe no código abaixo para que ele execute corretamente no Portugol Studio:[cite: 5]
   ```portugol
   programa {
     funcao inicio() {
       escreva("Olá, mundo!")
     }
   }
   ```
3. Crie um programa sequencial que exiba na tela três mensagens diferentes em três linhas separadas, utilizando o caractere de quebra de linha `\n`[cite: 5].
4. Escreva um algoritmo chamado "Receita". Ele deve exibir o passo a passo de como fazer um sanduíche, imprimindo uma instrução por linha na ordem correta[cite: 5].
5. Complete o programa abaixo para que ele faça sentido e compile sem erros:[cite: 5]
   ```portugol
   programa {
     funcao inicio() {
       escreva ("Programa iniciado!")
     }
   }
   ```

### 2. Dados, Tipos, Constantes e Variáveis
6. Escreva um programa que declare cinco variáveis, uma para cada tipo primitivo (`inteiro`, `real`, `cadeia`, `caracter` e `logico`), atribua valores e os exiba na tela[cite: 5].
7. Reescreva o código abaixo corrigindo os erros de tipo (atribuição incorreta):[cite: 5]
   * `inteiro idade = 20`[cite: 5]
   * `real altura = 1.75`[cite: 5]
   * `cadeia nome = "A"`[cite: 5]
   * `logico trabalha = verdadeiro`[cite: 5]
8. Crie um programa que declare uma constante `PI = 3.14159` e uma variável real `raio = 5.0`. Calcule e exiba a área de um círculo ($\acute{A}rea = PI * raio * raio$)[cite: 5].
9. Escreva um algoritmo que declare `A = 10` e `B = 3`. Calcule e mostre o resultado de `A / B` e o resto da divisão `A % B`[cite: 5].
10. Utilizando a biblioteca `Matematica`, calcule a raiz quadrada de 144 e o valor de $2^8$ (potência)[cite: 5].
11. Faça o teste de mesa: qual o valor de `z` se `x = 5`, `y = 2` e `z = x + y * 3`? (Resposta: 11)[cite: 5].

### 3. Entrada, Saída e Atribuição
12. Crie um algoritmo que solicite o nome e a cidade do usuário e exiba: "Olá [nome], você mora em [cidade]!"[cite: 5].
13. Leia dois números reais, some-os e exiba o resultado em uma terceira variável[cite: 5].
14. Corrija o comando de leitura: `leia(idade)` em vez de `leia("idade")`[cite: 5].
15. Leia o valor de um produto e aplique um desconto de 15%[cite: 5].
16. Converta uma temperatura de Celsius para Fahrenheit: $F = (C * 1.8) + 32$[cite: 5].
17. Troque os valores de duas variáveis (A para B e B para A) usando uma variável auxiliar[cite: 5].

### 4. Estruturas Seletivas (Condicionais)
18. Leia um número inteiro e informe se ele é par ou ímpar usando o operador `%`[cite: 5].
19. Verifique se o usuário é "Maior de idade" (>= 18) ou "Menor de idade"[cite: 5].
20. Complete o sistema de notas: Aprovado (>= 7), Recuperação (>= 5 e < 7) ou Reprovado (< 5)[cite: 5].
21. Leia dois números e informe qual é o maior ou se são iguais[cite: 5].
22. Use `escolha...caso` para ler um número de 1 a 7 e imprimir o dia da semana correspondente[cite: 5].
23. Refatore múltiplos `se` para uma estrutura `escolha...caso` com as opções: 1-Novo Jogo, 2-Carregar, 3-Sair[cite: 5].
24. Calcule a idade do usuário e verifique se ele já pode votar (>= 16 anos)[cite: 5].

### 5. Estruturas Repetitivas (Laços)
25. Use `enquanto` para fazer uma contagem regressiva de 10 até 1[cite: 5].
26. Use `para` para exibir todos os números pares entre 2 e 20[cite: 5].
27. Corrija um loop infinito adicionando o incremento `cont++` (ou `cont = cont + 1`)[cite: 5].
28. Use `faca...enquanto` para pedir uma senha até que o usuário digite "1234"[cite: 5].
29. Leia 5 números usando `para`, some-os e exiba a média aritmética[cite: 5].
30. Teste o laço aninhado: quantas vezes a mensagem será impressa se o laço externo for de 1 a 3 e o interno de 1 a 2?[cite: 5]
31. Converta um laço `para` em um laço `enquanto` mantendo o mesmo resultado[cite: 5].

### 6. Desafios Integradores
32. **Tabuada:** Peça um número e mostre sua tabuada de 1 a 10 usando `para`[cite: 5].
33. **Calculadora:** Leia dois números e ofereça um menu (Soma, Subtração, Multiplicação, Divisão) usando `escolha...caso`[cite: 5].
34. **Fatorial:** Calcule o fatorial de um número fornecido pelo usuário (ex: $5! = 5 * 4 * 3 * 2 * 1 = 120$)[cite: 5].
35. **Jogo de Adivinhação:** Defina um número secreto e use `enquanto` com dicas de "Muito alto" ou "Muito baixo" até o acerto[cite: 5].
```
```
