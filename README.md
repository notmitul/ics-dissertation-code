# ICS Dissertation Code

**Semi-analytical modeling of inverse-Compton scattering spectra using Python**

This repository contains the full codebase developed as part of an M.Sc. Physics (Astrophysics specialization) dissertation. The project models inverse-Compton scattering (ICS) spectra using semi-analytical expressions in the Thomson regime, focusing on both thermal (blackbody) and non-thermal (power-law) photon seed fields.

---

## 🔗 Launch in Google Colab

Click below to run the demo notebook in your browser with no installation required:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/your-username/ics-dissertation-code/blob/main/main.ipynb)

---

## 🧰 Features

- Modular Python implementation (`electrons.py`, `photons.py`, etc.)
- Computes Spectral Energy Distributions (SEDs) and Spectral Number Distributions (SNDs)
- Supports blackbody and power-law seed photon fields
- Reproducible and validated against analytical expectations

---

## 📁 Code Structure

| File                | Description                                      |
|---------------------|--------------------------------------------------|
| `electrons.py`      | Electron energy distributions                    |
| `photons.py`        | Blackbody and power-law photon fields            |
| `normalize.py`      | Integration and energy-density normalization     |
| `inverse_compton.py`| ICS spectrum calculation (Thomson regime)        |
| `main.ipynb`        | Example notebook for Colab/demo use              |

---

## 📊 Example Output

The demo notebook (`main.ipynb`) produces a sample ICS SED for:
- \( \alpha = 2.0 \)
- \( \gamma_{\min} = 10^2 \), \( \gamma_{\max} = 10^5 \)
- Planck photon field at \( T = 2.72 \,\mathrm{K} \)

---

## 🧪 Validation

- Emissivity scaling \( \epsilon_s \sim \gamma^2 \epsilon \) confirmed
- Compared against Blumenthal & Gould (1970)

---

## 📜 License & Citation

This project is licensed under the **GNU General Public License v3.0**.  
You are free to use, modify, and distribute the code, provided that:
- The same license is applied to any derived work.
- Proper attribution is given to the original author.

The full license text is available here:  
[https://www.gnu.org/licenses/gpl-3.0.en.html](https://www.gnu.org/licenses/gpl-3.0.en.html)

### 📚 How to Cite

If you use this code or dissertation in your work, please cite it as:

**Dissertation:**

Mitul Singh. (2025). *Study of inverse-Compton Scattering of photons by electrons* (Master’s dissertation). [AUUP].

**GitHub Repository:**

Mitul Singh. (2025). *ics-dissertation-code* [Computer software]. GitHub. https://github.com/notmitul/ics-dissertation-code

---

## 📬 Contact

For questions, suggestions, or collaborations:
- 📧 Email: mitulsingh.02@yahoo.com
- 🔗 GitHub: [github.com/notmitul](https://github.com/notmitul)

