# Default Methods Java (defender methods) 

---

- A partir do Java 8, interfaces podem conter m�todos concretos
- A inten��o b�sica � prover implementa��o padr�o para m�todos, de modo a evitar:
 * Repeti��o de implementa��o em toda classe 
 * A necessidade de se criar classes abstratas para reuso
 * Manter a retrocompatibilidade 
 * Permitir que interfaces funcionais possam prover outras opera��es padr�o reutiliz�veis.

### Problema exemplo
Fazer um programa para ler uma quantia e a dura��o em meses de um empr�stimo. Informar o valor a ser pago depois de decorrido o prazo do empr�stimo, conforme regras de juros do Brasil. A regra de c�lculo de juros do Brasil � juro composto padr�o de 2% ao m�s.

---

### Considera��es extras

- Interfaces podem prover reuso
- Temos uma forma de heran�a m�ltipla
  * Mas o compilador reclama se houve mais de um m�todo com a mesma assinatura, obrigando a sobrescrever
- Interfaces ainda s�o bem diferentes de classes abstratas. Interfaces n�o possuem recursos tais como construtores e atributos.