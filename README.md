# Aluminium Rod Compression Testing

Group project investigating aluminium as a prosthetic material under real-world physiological loading and temperature conditions, combining Instron compression testing with SolidWorks FEA.

🌐 **[Live interactive report](https://mahdifetanat.github.io/Aluminium-Website/)**

📄 **[Poster](https://github.com/mahdifetanat/Aluminium-Material-Analysis/blob/main/Instron%20poster.pdf)**

## The question

How does an aluminium rod behave under compressive loads and temperature swings similar to what a prosthetic limb experiences day to day?

## Method

**Instron compression testing** on a ⌀3.98 × 8.53 mm aluminium rod across three test protocols:
- **Test 1 — Ramp rate comparison**: single load-unload cycle to 2500N, comparing 200 N/s vs 300 N/s ramp rates to isolate viscoelastic (rate-dependent) behaviour from pure elastic response
- **Test 2 — High-amplitude cyclic loading**: 250 cycles at 0.77Hz (800N base, 700N amplitude), repeated at −18°C, 5°C, and 38°C to simulate real thermal extremes a prosthetic might face
- **Test 3 — Low-amplitude cyclic loading**: 300 cycles at 0.5Hz (330N base, 320N amplitude), same three temperatures, to see how amplitude affects long-term stability

**SolidWorks FEA** — nonlinear static simulations of each test condition, validating experimental stress/displacement results against Von Mises stress distribution and factor of safety, using measured material properties

## Key findings

- Compression rate affects apparent stiffness
- Lower-amplitude cyclic loading caused the material to show a  stiffer linear-elastic behaviour, with a sharp effect on cycle 1 followed by a stable plateau. Higher-amplitude loading showed gradual stiffness decay over cycles
- The temperature at which the material was stiffest actually reversed between the two amplitude regimes, showing the thermal response is amplitude-dependent rather than fixed
- FEA cross-validated the experimental stress and displacement results, giving a factor of safety analysis across all four loading conditions
