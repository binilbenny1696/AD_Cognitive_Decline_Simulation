# 🧠 AD_Cognitive_Decline_Simulation

This project simulates **Alzheimer's disease progression** over 5 years using **Simulx**, evaluating the impact of **mild vs. strong drug interventions** on cognitive decline modeled via MMSE score. A delayed drug effect model and corrected progression rate are implemented to study disease dynamics in a simulated patient population.

---

## 🧪 Objective

- Simulate untreated vs. treated Alzheimer’s populations over 5 years.
- Model delayed drug effect using a **T50-based nonlinear function**.
- Quantify impact of treatment strength on **median time to cognitive worsening** (MMSE < 24).
- Visualize population-level progression and % of patients worsening over time.

---

## 🧰 Tools Used

| Category         | Tools         |
|------------------|---------------|
| Disease Modeling | Simulx (Monolix Suite) |
| Analysis         | R, Excel      |
| Output Metrics   | MMSE score, Time to MMSE<24, % worsened |

---

## 📂 Project Structure


---

## 📈 Key Results

| Group       | Median Time to MMSE < 24 | % Patients Worsened |
|-------------|---------------------------|----------------------|
| Untreated   | ~3.0 years                | 100%                |
| Mild Drug   | ~3.4 years                | 92%                 |
| Strong Drug | ~4.2 years                | 66%                 |

- Strong drugs delayed worsening by ~1 year and reduced progression rate by 26%.
- Mild intervention had limited clinical benefit.

---

## 📚 References

- Literature-based MMSE decline parameters for Alzheimer’s progression
- Simulx modeling framework for longitudinal simulations

---

## 👨‍💻 Author

**Binil Benny**  
QSP & Disease Progression Modeling | Simulx | PK/PD Simulation  
GitHub: [@binilbenny1696](https://github.com/binilbenny1696)

---

## 🪪 License

This project is licensed under the [MIT License](LICENSE).
