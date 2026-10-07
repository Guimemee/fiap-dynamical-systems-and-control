# Origem e Justificativa do Problema

**Disciplina:** Dynamical Systems & Control
**Ano Letivo:** 2025 | **Turma:** 4ECS
**Avaliação:** Checkpoint 4

### Enunciado do Problema
Dimensionar um controlador PID analítico usando o método de alocação de polos para atender aos requisitos de ultrapassagem percentual Mp <= 4.3% e tempo de acomodação ts <= 1.0 s.

### Formulação Formal
$$C(s) = K_p + \frac{K_i}{s} + K_d s = \frac{K_d s^2 + K_p s + K_i}{s}, \quad \zeta \ge 0,707, \quad \omega_n \ge 4 \text{ rad/s}$$
