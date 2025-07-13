# DAL Project
Designed an inverter-based oscillator and used the Dynamic Autonomous Loading (DAL) method to reduce startup time. Simulated the circuit in Cadence Virtuoso and analyzed improvements in oscillation behavior.
## Approach
We started by deriving the fundamental equations governing oscillator behavior.
MATLAB was used to plot these relationships and observe key trends and dependencies.
The overall problem was divided into smaller, manageable sub-blocks to enable modular analysis.
Each sub-block was examined and implemented in a sequential manner.
The full system was ultimately simulated using Cadence Virtuoso.
## Key Benefits and Startup Dynamics of the Proposed Oscillator
The proposed oscillator is optimized for energy-efficient performance, making it highly suitable for power-constrained systems. Its fast start-up capability ensures stable oscillation is reached quickly after power-on.

Key Advantages:

- Low Power Operation: Perfect for battery-powered or energy-harvesting applications.

- Fast Start-Up: Reduces delay in system activation.

- Autonomous Load Adjustment:

-- Temporarily increases load during startup to enhance oscillation buildup.

-- Reduces load post-startup to save power in steady-state conditions.

Factors Influencing Startup Time:
Startup time is affected by multiple parameters. A higher quality factor (Q) generally leads to slower startup as the system takes longer to build oscillations. Negative resistance (|RN|) plays a vital role in overcoming inherent losses and enabling the oscillator to initiate. Additionally, operating at higher frequencies tends to reduce the startup time, allowing the system to stabilize more quickly.
