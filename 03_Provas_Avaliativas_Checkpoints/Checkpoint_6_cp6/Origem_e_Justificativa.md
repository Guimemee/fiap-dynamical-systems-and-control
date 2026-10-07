# Origem e Justificativa do Problema

**Disciplina:** Dynamical Systems & Control
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 6

### Enunciado do Problema
Representar o manipulador robótico em espaço de estados dx/dt = Ax + Bu, y = Cx e verificar as matrizes de controlabilidade de Kalman e observabilidade, projetando regulador LQR.

### Formulação Formal
$$\mathcal{C} = [B \quad AB \quad A^2B], \quad \text{rank}(\mathcal{C}) = n, \quad J = \int_0^\infty (x^T Q x + u^T R u) dt$$
