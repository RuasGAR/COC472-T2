# COC472 (Computação de Alto Desempenho)

## Trabalho 2 - Estudo de caso de otimizações automáticas e manuais

Este repositório contém o código fonte de um programa de solução de sistemas lineares pelo Método de Jacobi, disponibilizado publicamente pela Universidade de Boston.

- Os executáveis estão dispostos somente porque são fundamentais no estudo proposto: averiguar os impactos de otimizações de flags, especificamente do compilador **gcc**, bem como as melhorias manuais e assistidas por perfiladores.

- Para as análises, foram utilizados os programas:

  - gprof: perfilador que acompanha os compiladores da GNU
  - perf: programa utilitário das distribuições Linux; de caráter mais geral, ele é usado intercambiadamente para análise de memória, e.g. L1 cache, e análise de tempo de execução

- O repositório acompanha um relatório dos experimentos.
