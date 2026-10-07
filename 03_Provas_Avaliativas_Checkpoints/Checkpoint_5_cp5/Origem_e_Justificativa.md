# Origem e Justificativa do Problema

**Disciplina:** Dynamical Systems & Control
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 5

### Enunciado do Problema
Dimensionar um compensador por avanço de fase (Lead Compensator) para garantir Margem de Fase MF >= 55 graus e Margem de Ganho MG >= 12 dB na esteira de montagem inteligente.

### Formulação Formal
$$G_c(s) = \frac{1 + \alpha T s}{1 + T s}, \quad \alpha = \frac{1 + \sin\phi_m}{1 - \sin\phi_m}, \quad \omega_m = \frac{1}{T\sqrt{\alpha}}$$
