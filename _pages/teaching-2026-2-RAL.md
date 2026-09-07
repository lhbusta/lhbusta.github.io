---
permalink: /teaching/2026.2-RAL/
title: "Raciocínio Automatizado via Lógica (CC0098) — 2026.2"
excerpt: "Plano de curso (optativa) — Universidade Federal do Cariri, 2026.2"
author_profile: true
---

- Professor: Luis Henrique B. de Morais
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

## Metodologia

Aulas expositivas acompanhadas de laboratórios práticos com solvers SAT/SMT (Z3, cvc5) e discussão de artigos.

## Avaliação

MF = 0,3×NL + 0,3×AV1 + 0,4×AV2

Caso AV1 < 3,0, o aluno poderá optar por: MF = 0,3×NL + 0,7×AV2

## Cronograma do Curso

1. Apresentação da disciplina / motivação
2. Revisão de lógica proposicional
3. Formas normais (CNF, DNF) e Tseitin
4. O problema da satisfatibilidade (SAT)
5. Complexidade de SAT — NP-completude
6. Algoritmo DPLL
7. Heurísticas de decisão em DPLL
8. CDCL — aprendizado de cláusulas
9. CDCL — VSIDS e reinícios (restarts)
10. Revisão de lógica de primeira ordem
11. Satisfatibilidade Módulo Teorias (SMT)
12. Teorias decidíveis (aritmética, arrays, uninterpreted functions)
13. Método de Nelson-Oppen (combinação de teorias)
14. Solvers modernos: Z3 e cvc5
15. Aplicações: verificação de programas

## Bibliografia

- Handbook of Satisfiability
- First-Order Logic and Automated Theorem Proving

## Bibliografia Complementar

- [SAT/SMT by Example](https://sat-smt.codes/SAT_SMT_by_example.pdf)
- [Z3 Guide](https://microsoft.github.io/z3guide/)
- [cvc5 Python API](https://cvc5.github.io/docs/cvc5-1.0.2/api/python/python.html)
