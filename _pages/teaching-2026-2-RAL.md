---
permalink: /teaching/2026.2-RAL/
title: "Raciocínio Automatizado via Lógica (CC0098) — 2026.2"
excerpt: "Plano de curso (optativa) — Universidade Federal do Cariri, 2026.2"
author_profile: true
---

- Professor: Luis Henrique B. de Morais
- Sala: K05
- Horário: Terça e Quinta — 14h

## Ementa

Lógica proposicional e de Primeira-ordem. Problema da satisfatibilidade (SAT) e suas versões. Procedimentos clássicos de satisfatibilidade proposicional: DPLL e CDCL. Satisfatibilidade Módulo Teorias e solvers modernos.

## Programa

- Revisão de lógica proposicional e de primeira ordem
- Formas normais e o problema da satisfatibilidade (SAT)
- Procedimentos de decisão: DPLL e CDCL
- Satisfatibilidade Módulo Teorias (SMT)
- Solvers modernos (Z3, cvc5) e aplicações

## Objetivos

- Implementações:
  - DPLL
  - CDCL
  - DPLL(T)

## Metodologia

Aulas expositivas acompanhadas de laboratórios práticos com solvers SAT/SMT (Z3, cvc5) e discussão de artigos.

## Avaliação

A avaliação é composta por três implementações e um seminário:

MF = w1×E1 + w2×E2 + w3×E3 + w4×SEM

onde:

- **E1** — Entrega 1: DPLL com watched literals
- **E2** — Entrega 2: CDCL completo
- **E3** — Entrega 3: DPLL(T)/CDCL(T) com EUF e Difference Logic
- **SEM** — Seminário: apresentação de artigo de pesquisa

As listas de exercícios não têm nota própria: elas contam como pontos no trabalho (entregas de implementação).

## Cronograma do Curso

1. Apresentação da disciplina / motivação
2. Revisão de lógica proposicional
3. Formas normais (CNF, DNF) e Tseitin
4. O problema da satisfatibilidade (SAT)
5. Complexidade de SAT — NP-completude
6. Algoritmo DPLL
7. Heurísticas de decisão em DPLL
8. Exercícios / laboratório (DPLL)
9. CDCL — aprendizado de cláusulas
10. CDCL — VSIDS e reinícios (restarts)
11. Exercícios / laboratório (CDCL)
12. Revisão de lógica de primeira ordem
13. Satisfatibilidade Módulo Teorias (SMT)
14. Teorias decidíveis (aritmética, arrays, uninterpreted functions)
15. Método de Nelson-Oppen (combinação de teorias)
16. Solvers modernos: Z3 e cvc5
17. Laboratório com Z3/cvc5
18. Aplicações: verificação de programas

## Bibliografia

- KROENING, D.; STRICHMAN, O. *Decision Procedures: An Algorithmic Point of View*. 2ª ed. Springer, 2016.
- BRADLEY, A. R.; MANNA, Z. *The Calculus of Computation: Decision Procedures with Applications to Verification*. Springer, 2007.

## Bibliografia Complementar

- BIERE, A. et al. *Handbook of Satisfiability*. 2ª ed. IOS Press, 2021.
- FITTING, M. *First-Order Logic and Automated Theorem Proving*. 2ª ed. Springer, 1996.
- [SAT/SMT by Example](https://sat-smt.codes/SAT_SMT_by_example.pdf)
- [Z3 Guide](https://microsoft.github.io/z3guide/)
- [cvc5 Python API](https://cvc5.github.io/docs/cvc5-1.0.2/api/python/python.html)
