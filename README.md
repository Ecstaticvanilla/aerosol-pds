# Aerosol Classification in Africa

## Project Description

This project focuses on the classification of aerosols across the African continent using machine learning. The analysis leverages a multivariate spectral clustering algorithm on data from 17 AERONET sites in Africa. The primary objective is to identify and classify the dominant aerosol types to better understand their effects on the Earth's energy budget and help in developing climate change policies.

---

## Key Features

| Feature | Description |
| :--- | :--- |
| **Data Source** | Utilizes quality-assured data from the **AER**osol **R**obotic **N**etwork (AERONET) from 17 sites across Africa, collected between October 1995 and January 2022. |
| **Machine Learning** | Employs a spectral clustering algorithm, as suggested by an academic paper, but also explores other algorithms. The combination of **Principal Component Analysis (PCA)** for dimensionality reduction followed by **K-Means clustering** was found to yield superior results compared to spectral clustering alone. |
| **Data Preprocessing** | The raw data is cleaned to remove missing values, which were represented by "-999". The notebook also includes code to calculate aerosol properties like Extinction Ångström Exponent (EAE) and Absorption Ångström Exponent (AAE) based on the Dubovik and King formulae, enabling a comparison with the data provided. |
| **Aerosol Classification** | The project successfully classifies aerosols into four primary types: dust, urban, biomass burning, and mixed aerosols. |
| **Data-Driven Insights** | The analysis demonstrates that dust aerosols have the highest contribution among the sites studied, which is consistent with the region's status as a major global dust source. |

---

## Usage

1.  Download both the `aerosolafrica.ipynb` notebook and the `africa.csv` data file.
2.  Place both files in the same directory.
3.  Launch Jupyter Notebook and open `aerosolafrica.ipynb`.
4.  Run the cells sequentially to see the full data processing, analysis, and visualization of the results.

---

## References

* Shantikumar S. Ningombam, E.J.L. Larson, G. Indira, B.L. Madhavand, Pradeep Khatri, "Aerosol classification by application of machine learning spectral clustering algorithm", *Atmospheric Pollution Research*.