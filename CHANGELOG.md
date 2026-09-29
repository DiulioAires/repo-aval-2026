# Changelog

Todas as mudanças relevantes deste projeto são documentadas neste arquivo.

O formato segue o [Keep a Changelog](https://keepachangelog.com/pt-BR/1.1.0/)
e o projeto adota o [Versionamento Semântico](https://semver.org/lang/pt-BR/).

## [1.1.0] - 2026-09-28

### Adicionado

- Formatação da média com uma casa decimal e vírgula como separador.
- Situação "Aprovado com distinção" para médias a partir de 9,0.
- Testes para notas inválidas e para os limites de 0 a 10.

### Alterado

- Cálculo da média reescrito com métodos de array, sem o laço `for`.

### Corrigido

- Médias exatamente iguais a 7,0 agora resultam em aprovação.

## [1.0.0] - 2026-09-14

### Adicionado

- Cálculo da média aritmética das notas.
- Classificação da situação do aluno: Aprovado, Recuperação ou Reprovado.
- Execução pela linha de comando (`npm start -- <notas>`).
- Integração contínua com testes e verificação de Conventional Commits.
