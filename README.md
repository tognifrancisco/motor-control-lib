# Motor Control Library for Embedded Systems

Multi-axis motor control library for ARM Cortex-M and TI C2000. Designed 
for distributed motion control systems with encoder feedback.

## Features

- **PID controller** with anti-windup and feed-forward
- **Ramps** — trapezoidal and S-curve profiles
- **Quadrature encoder decoding** — 1x/2x/4x modes
- **Current loop** — FOC-ready, Clarke/Park transforms
- **Multi-axis orchestration** — coordinated motion profiles

Platforms

    STM32F4 / F7 / H7 (HAL, TIM encoder mode)

    TI TMS320F280049 (C2000, eQEP, ePWM)

    Generic Cortex-M (bare metal)

Status

Actively used in multi-axis motion control products (client projects).
License

MIT — see LICENSE.
