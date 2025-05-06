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

| Design No.                | Area (nm²) | Power (nW) | Delay (ns) | PDP (aJ) | FoM (1 / (PDP × Area)) |
| ------------------------- | ---------- | ---------- | ---------- | -------- | ---------------------- |
| Proposed Design (in 45n)  | 154000     | 1.71       | 3.645      | 6.236    | 1.043 × 10⁻⁶           |
| Proposed Design (in 180n) | 1694550    | 3.497      | 8.671      | 30.32    | 1.942 × 10⁻⁸           |
| Paper a                   | 1048200    | 478.8      | 4.157      | 1990.37  | 4.766 × 10⁻¹⁰          |
| Paper b                   | 180400     | 2.268      | 3.53       | 8.006    | 6.922 × 10⁻⁷           |
| Paper c                   | 8580800    | 17620      | 3.21       | 56560.2  | 2.057 × 10⁻⁹           |
| Paper d                   | 495800     | 6.833      | 3.45       | 23.59    | 8.618 × 10⁻⁸           |
| Paper g                   | 168000     | 2.71       | 3.483      | 9.435    | 6.316 × 10⁻⁷           |
| Paper h                   | 378000     | 1964.0     | 3.65       | 7168.6   | 3.682 × 10⁻⁹           |


## Note
- All values of FoM are in \( \text{nm}^{-2} \cdot \text{aJ}^{-1} \).
- Lower PDP and higher FoM are desired for efficient design.

---


In 180nm design the overall dynamic power dissipation increases due to increase in the value of capacitance.



# Design 3 ( Paper a )

Delay 4.26ns

![image](https://github.com/user-attachments/assets/c0f52c2b-76e4-4076-b88f-3474cbf66ac4)




Power


