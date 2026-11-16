# QuFi-HackClub-Project
This is a macropad specifically designed for excel shortcuts for accounting in public companies and private companies. Its more relevant for public companies who have to track and show certain data to shareholders.

# QuFi

### **A custom macropad that simplifies accounting and financial analysis.**

![ExcelPad fully assembled](images/hero-shot.jpg)

---

# ❓ What Is This? 

**QuFi** is a macropad that brings some of the most commonly used financial formulas into excel with no technical experience
required. It uniquely offers both commonly used preloaded formulas, as well as customizable layers in a library of financial formulas or you can bring your own formulas! 

---

# ⚙️ What Does It Do?

- **GAAP Accounting Formulas:** QuFi Comes preloaded with 27 GAAP Accounting formulas with everything from calculating assets to Income Calculations
- **Full Customizable Library:** I'm currently working on a libarary to bring almost any excel accounting or corporate finance formula to QuFi which will allow users the change their configurationa and quick formulas.
- **Custom Formulas:** I'm working on documentation for users to create their own formulas either by themselves or using AI to apply to QuFi.

## Key Layout

| Key | Action | Shortcut Sent |
|-----|--------|---------------|
| 1 | Accounting equation check (should equal 0) | =Assets-(Liabilities+Equity) |
| 2 |Gross profit | =Revenue-COGS |
| 3 | Net income | 	=Revenue-Expenses |
| 4 | Gross margin % | =(Revenue-COGS)/Revenue |
| 5 | Working capital | =CurrentAssets-CurrentLiabilities |
| 6 | Current ratio| =(Cash+AR+Securities)/CurrentLiabilities |
| 7 | Quick ratio | 	=Revenue-Expenses |
| 8 | Debt-to-equity | =TotalLiabilities/TotalEquity |
| 9 | Straight-line depreciation | =SLN(Cost,Salvage,Life) |
---

# 🔧 How To Use It

1. Plug it into your computer via USB-C.
2. Flash the firmware: [QMK / KMK / Arduino + steps or link].
3. Open Excel and press any key.
4. To change a key, edit `firmware/keymap` and reflash.
5. To directly select numbers used in the formula, click equals in the cell which the desired output should reside in, then click on all the relevant data in order they show up in the equation, then click the key on QuFi

---

# 💡 Why I Made This

[Describe the specific problem you were solving. Be personal and honest.]

---

# 🖼️ Gallery

## Full 3D Model (Assembled)
![3D Model](images/3d-model.png)

## PCB
![PCB](images/pcb.png)

## Wiring Diagram / Schematic
![Schematic](images/schematic.png)

---

# 🧰 Bill of Materials

| Part | Qty | Notes |
|------|-----|-------|
| [Microcontroller] | 1 | |
| Switches | [X] | |
| Keycaps | [X] | |
| Diodes | [X] | |

**Total cost:** ~$[X]

---

# 📁 Repository Structure

```
├── firmware/
├── pcb/
├── cad/
├── images/
└── README.md
```

---

# 📜 License

[MIT or other]
