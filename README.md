# ICS Dissertation Code

**Semi-analytical modeling of inverse-Compton scattering spectra using Python**

This repository contains the full codebase developed as part of an M.Sc. Physics (Astrophysics specialization) dissertation. The project models inverse-Compton scattering (ICS) spectra using semi-analytical expressions in the Thomson regime, focusing on both thermal (blackbody) and non-thermal (power-law) photon seed fields.

---

## 🔗 Launch in Google Colab

Click below to run the demo notebook in your browser with no installation required:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/your-username/ics-dissertation-code/blob/main/main.ipynb)

> 📌 Replace `your-username` with your GitHub handle after uploading the repo.

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
| `electrons.py`      | Electron energy distributions and normalization |
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

This code is made available under the GNU License.  
Please cite this repository or the dissertation if used in academic work:

> *Mitul CK, “Modeling Inverse-Compton Scattering Using Semi-Analytical Methods”, M.Sc. Dissertation, 2025*

---

## 📬 Contact

For questions, suggestions, or collaborations:
- 📧 Email: your.email@domain.com
- 🔗 GitHub: [github.com/your-username](https://github.com/your-username)

