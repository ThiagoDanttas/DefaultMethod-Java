# Default Methods Java (defender methods) 

---

- A partir do Java 8, interfaces podem conter métodos concretos
- A intenção básica é prover implementação padrão para métodos, de modo a evitar:
  * Repetição de implementação em toda classe 
  * A necessidade de se criar classes abstratas para reuso
  * Manter a retrocompatibilidade 
  * Permitir que interfaces funcionais possam prover outras operações padrão reutilizáveis.

### Problema exemplo
Fazer um programa para ler uma quantia e a duração em meses de um empréstimo. Informar o valor a ser pago depois de decorrido o prazo do empréstimo, conforme regras de juros do Brasil. A regra de cálculo de juros do Brasil é juro composto padrão de 2% ao mês.

---

### Considerações extras

- Interfaces podem prover reuso
- Temos uma forma de herança múltipla
  * Mas o compilador reclama se houve mais de um método com a mesma assinatura, obrigando a sobrescrever
- Interfaces ainda são bem diferentes de classes abstratas. Interfaces não possuem recursos tais como construtores e atributos.
