# UART ASIC Synthesis Results

## Technology

- **Synthesis Tool:** Yosys
- **Standard Cell Library:** Sky130 HD

---

## Top-Level Summary

| Metric | Value |
|:-------|------:|
| Top Module | `uart` |
| Total Standard Cells | **252** |
| Estimated Cell Area | **2620.0128** |
| Sequential Area | **1452.6432 (55.44%)** |

---

## Module Breakdown

| Module | Cells | Area |
|:-------|------:|-----:|
| RX | 104 | 1143.5968 |
| TX | 77 | 779.4976 |
| Baud Generator #1 | 24 | 245.2352 |
| Baud Generator #2 | 47 | 451.6832 |

---

## Hierarchy

```text
uart
├── baud_gen #1
├── baud_gen #2
├── rx
└── tx
```

---

## Synthesis Highlights

- Successfully synthesized RTL to Sky130 HD standard cells.
- Total standard cell count: **252**
- Estimated total cell area: **2620.0128**
- Sequential elements occupy **55.44%** of the synthesized design area.
- The RX module is the largest block, followed by the TX module.

---

## Cell Distribution

| Cell Type | Count |
|:----------|------:|
| D Flip-Flops (`dfrtp_1`) | 57 |
| Inverters (`clkinv_1`) | 62 |
| Multiplexers (`mux2_1`) | 25 |
