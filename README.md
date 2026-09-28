# Statistical Analysis of Public Trust in Traditional & Complementary Medicine in Turkey

An empirical undergraduate research project examining the multidimensional factors shaping public trust in traditional and complementary medicine (T&CM) healers in Turkey, utilizing the **Wellcome Global Monitor (WGM)** microdata ($N=790$).

---

## Key Empirical Findings

* **Institutional Alignment (Not Rejection):** Participants with high trust in medical doctors and nurses exhibit **4.71 times higher odds** ($Exp(B) = 4.707, p < 0.001$) of placing high trust in traditional healers compared to the low/limited trust reference group. Trust in healers operates as an integrated healthcare preference rather than a reaction against modern medicine.
* **Economic Capital as a Determinant:** Individuals with high perceived income levels exhibit **3.13 times higher odds** ($Exp(B) = 3.134, p = 0.002$) of trusting healers compared to the low-income reference group, pointing to T&CM utilization as a wellness and consumption lifestyle choice.
* **Methodological Optimization (MCA):** To eliminate the artificial variance inflation inherent to standard indicator and Burt matrices, an **Adjusted Burt Matrix** approach was implemented, achieving **88.0% cumulative explained inertia** across the first two dimensions.

---

## Methodology & Tech Stack

* **Software Tools:** R (RStudio), IBM SPSS Statistics
* **Statistical Methods:**
  * Multiple Correspondence Analysis (MCA) with Adjusted Burt Matrix
  * Multinomial Logistic Regression Modeling
  * Chi-Square ($\chi^2$) Tests of Independence
  * Factorial Biplots ($cos^2$ representation quality) & 95% Confidence Ellipses

---

## Visualizations

### 1. Factorial Biplot of Variable Categories
*Mapping multidimensional relationships across demographic and attitudinal variables along two primary axes:*

![MCA Biplot](mca_biplot.png)

### 2. Trust Clusters and 95% Confidence Ellipses
*Spatial distribution of participants segmented by healer trust levels:*

![Confidence Ellipses](confidence_ellipses.png)

---

## Repository Contents

* [`Yade_Irem_Bilgic_Lisans_Tezi.pdf`](./Yade_Irem_Bilgic_Lisans_Tezi.pdf): Complete undergraduate thesis text (in Turkish).
* [`analiz_kodlari.Rmd`](./analiz_kodlari.Rmd): R Markdown source code for data visualization and MCA models.
* [`analiz_raporu.html`](./analiz_raporu.html): Compiled R Markdown analysis output and visual reports.
* [`WGM_Turkiye_Veri_Seti_Ham.xlsx`](./WGM_Turkiye_Veri_Seti_Ham.xlsx): Raw Wellcome Global Monitor survey dataset.
* [`düzenlenmiş_veri.sav`](./düzenlenmiş_veri.sav): Cleaned and recoded SPSS dataset used for final modeling.
* [`çıktılar.spv`](./çıktılar.spv): Native SPSS statistical output files.
