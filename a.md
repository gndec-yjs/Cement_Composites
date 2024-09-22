### Appendix B: Illustrative Example for Validating the Analytical Model

#### Case Study: Set - I
- **Steel Fibre Volume Fraction (V_f):** 0.75%
- **Exposure Duration:** 1 month
- **Concrete Compressive Strength (f_ck):** 25 MPa
- **Beam Width (B):** 100 mm
- **Beam Depth (D):** 100 mm
- **Span Length (L):** 0.45 m (450 mm)

#### Input Parameters
- **Fibre Index (β):** 0.045
- **Gravimetric Loss (η_cal):** 41.3%
- **Actual Metal Loss (η):** 69.75%
- **Metal Loss Factor (f_l):** 
  \[
  f_l = 1 - η = 1 - 0.6975 = 0.3025
  \]
- **Stress Mobilization Factor (γ):** 0.87
- **Depth Ratio (m/D):** 0.4
- **Reinforcement Index (ω):** 0.314
- **Depth Ratio (d'/D):** 0.25
- **Aspect Ratio of Fibre (l/D):** 50
- **Fibre Length (L):** 0.45 m

#### Analytical Model
The maximum moment (\( M_u \)) in the beam is calculated using the formula:

\[
M_u = 0.064 \times f_{ck} \times B \times D^2
\]

Substituting the values:

\[
M_u = 0.064 \times 25 \, \text{MPa} \times 100 \, \text{mm} \times (100 \, \text{mm})^2
\]

Calculating:

1. \( (100)^2 = 10000 \, \text{mm}^2 \)
2. \( M_u = 0.064 \times 25 \times 100 \times 10000 \)
3. \( M_u = 1600000 \, \text{N.mm} \) or \( 1600 \, \text{kN.mm} \)

#### Calculation of Load (\( P_u \))

The load (\( P_u \)) applied at the center during the three-point bending test is given by:

\[
P_u = \frac{4 \cdot M_u}{L}
\]

Substituting the calculated moment:

\[
P_u = \frac{4 \cdot 1600 \, \text{kN.mm}}{450 \, \text{mm}}
\]

Calculating:

1. \( 4 \cdot 1600 = 6400 \, \text{kN.mm} \)
2. \( P_u = \frac{6400}{450} \approx 14.22 \, \text{kN} \)

#### Conclusion

The calculated load \( P_u \) for the three-point bending test under the specified conditions is approximately **14.22 kN**.

### Comparison of Calculated and Experimental Values

| Parameter                 | Value (kN) |
|---------------------------|------------|
| Calculated Load \( P_u \) | 14.22      |
| Experimental Load         | 14.40      |

The experimental value for this case was found to be **14.40 kN**, indicating a close alignment with the calculated value.
