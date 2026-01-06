# Variáveis

As **variáveis** são espaços na memória do computador usados para armazenar dados que podem ser acessados e modificados durante a execução de um programa.
Em termos simples, uma variável é como uma “caixa” com um **nome** (identificador) e um **valor** dentro dela.

---

## 🔹 Declaração de variáveis

A forma de declarar variáveis muda conforme a linguagem, mas o conceito é o mesmo: criar um identificador para armazenar um dado.

### Exemplo geral:

```pseudo
variavel idade = 25
variavel nome = "Felipe"
variavel altura = 1.70
```

Nomeação de variáveis (boas práticas)
Use nomes descritivos: idade, notaFinal, precoProduto
Evite abreviações confusas ou genéricas: a, x1, temp2
Em linguagens case sensitive, idade e Idade são variáveis diferentes.

Use convenções da linguagem:
Python → snake_case → nome_completo
Java, JavaScript, C, PHP → camelCase → nomeCompleto

🔹 Escopo de variáveis

O escopo define onde uma variável pode ser acessada.
Global → pode ser usada em qualquer parte do código.
Local → só pode ser usada dentro de uma função, laço ou bloco específico.

🔹 Tipagem

Dependendo da linguagem, a variável pode precisar ter um tipo definido no momento da declaração:
Tipagem estática (C, Java) → é preciso declarar o tipo:
int idade = 25;
Tipagem dinâmica (Python, JavaScript, PHP) → o tipo é inferido automaticamente:
idade = 25

Reatribuição

O valor de uma variável pode ser alterado a qualquer momento, desde que respeite o tipo (em linguagens tipadas estaticamente):
idade = 25
idade = 26

⚙️ Resumo:
Variáveis armazenam informações temporárias, podem ter diferentes tipos e escopos, e são essenciais para qualquer lógica de programação.