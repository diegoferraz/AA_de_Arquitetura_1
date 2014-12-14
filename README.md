AA-ARQUITETURA-1_2014.2
=======================
Simulador MIPS feito para a Atividade Acadêmica de Arquitetura 1.

Universidade Federal Rural do Rio de Janeiro

Grupo: Vanessa Soares
       Patrícia Wang
       Diego Amaro

Professor: Filipe Braida do Carmo

Desenvolvido em : JavaScript
Browser utilizado: Mozilla Firefox

obs: Recomendamos usar apenas o Mozilla para o simulador.

Exemplo de instruções utilizadas:

// -------------------------------- Para apresentar erros:
addi $zero, $t1, 10
addi $sp, $t1, 9
mult $t1, 9
addi $t3, $a0, $a1
lw $t1, -2($a1)
sub $a1, $a5, $f9
sw $a2, 7($t2)

// -------------------------------- Para apresentar acertos:

addi $a1, $t1, 10
addi $t1, $t1, 9
li $a3, 98
mult $t1, $a1
addi $t3, $a0, 8
sw $t3, 0($s0)
lw $t4, 0($s0)
slt $t0, $t1, $a1
sub $a2 $a3, $t4
------------------------------------------------------------

addi $t0 $t0 2
addi $t1 $t1 4
bne $t0 $t1 label
li $v0 22
label:
li $v1 23
li $t3 99
