Why is the VDDL = 0.6 and VDDH = 1.8

# Power, Area, and Delay Comparison of Level Shifter Designs

This table compares various level shifter designs based on key performance metrics: Area, Power, Delay, Power-Delay Product (PDP), and a derived **Figure of Merit (FoM)**.

## Metrics Explained

- **Area (nm²):** Physical silicon area occupied by the design.
- **Power (nW):** Average power consumed during operation.
- **Delay (ns):** Propagation delay of the signal through the design.
- **PDP (aJ):** Power-Delay Product, calculated as Power × Delay, representing the energy per switching event.
- **FoM:** Figure of Merit, calculated as \( \text{FoM} = \frac{1}{\text{PDP} \times \text{Area}} \). A higher FoM indicates a better trade-off between power, speed, and area.

## Comparison Table

| Design No.                 | Area (nm²) | Power (nW) | Delay (ns) | PDP (aJ) | FoM (1 / (PDP × Area))          |
|---------------------------|------------|------------|------------|----------|---------------------------------|
| Proposed Design (in 45n)  | 69300      | 0.9667     | 3.99       | 3.857    | 3.703 × 10⁻⁶                    |
| Proposed Design (in 180n) | 922500     | 1.995      | 5.69       | 11.35    | 9.638 × 10⁻⁸                    |
|  Paper a                  | 1048200     | 478.8nW      | 4.157n       | 1990.37  | 8.630 × 10⁻¹⁰                   |
|  Paper b                  | 180400        | 2.268nW       | 3.53n        | 8.006    | 3.423 × 10⁻⁴                    |
|  Paper c                  | 8580800         | 17620nW       | 3.21n        | 56560.2    | 4.007 × 10⁻⁴                    |
|  Paper d                  | 495800        | 9.75nW       | 3.43n        | 42.63    | 2.889 × 10⁻⁴                    |
| Design 7                  | 105        | 13.4       | 2.0        | 26.80    | 3.538 × 10⁻⁴                    |
| Design 8                  | 125        | 15.9       | 1.7        | 27.03    | 2.946 × 10⁻⁴                    |
| Design 9                  | 90         | 10.5       | 2.4        | 25.20    | 4.405 × 10⁻⁴                    |
| Design 10                 | 100        | 12.0       | 2.1        | 25.20    | 3.968 × 10⁻⁴                    |
| Design 11                 | 115        | 13.8       | 1.8        | 24.84    | 3.497 × 10⁻⁴                    |

## Note
- All values of FoM are in \( \text{nm}^{-2} \cdot \text{aJ}^{-1} \).
- Lower PDP and higher FoM are desired for efficient design.

---


In 180nm design the overall dynamic power dissipation increases due to increase in the value of capacitance.



# Design 3 ( Paper a )

Delay 4.26ns

![image](https://github.com/user-attachments/assets/c0f52c2b-76e4-4076-b88f-3474cbf66ac4)

Power


