# Marcel Duchamp Social Network N-Gram Dataset

**Author:** Felipe Eduardo Lázaro Braga  
**Related project:** Marcel Duchamp Ego Network Dataset  
**Source:** Google Books N-Gram Viewer (English Corpus)  
**License:** Creative Commons Attribution 4.0 International (CC-BY 4.0)

---

## Description

This dataset compiles **Google Books N-Gram frequencies** for the **434 individuals** who form the documented social network of the Franco-American artist Marcel Duchamp (Braga, 2023).

The dataset was constructed using the **Google Books N-Gram Viewer**, a platform that measures the frequency with which words, expressions, or phrases appear in a large corpus of digitized books from the Google Books project.

For example, when a user searches for the expression *"Marcel Duchamp"* in the N-Gram Viewer, the platform calculates the proportion of **Two-Grams** in the selected corpus that correspond to this expression. In 2022, approximately **0.0000165233%** of all Two-Grams in the corpus corresponded to the expression “Marcel Duchamp”.

The goal of this dataset is to provide **longitudinal indicators of cultural visibility** for the individuals documented in Duchamp’s social network.

---

## Dataset Structure

The dataset is distributed as a **Microsoft Excel (.xlsx) file** with four sheets:

### Sheet 1 — Node Variables and N-Gram Data

This sheet contains:

- Sociodemographic attributes of each node
- N-Gram frequency measurements
- Variables derived from the frequency values

Each row corresponds to **one individual in the Duchamp network**.

### Sheet 2 — Introduction to Google N-Grams

This sheet provides a **brief methodological explanation** of the Google Books N-Gram Viewer and the principles behind the frequency calculations.

### Sheet 3 — Variable Dictionary

This sheet contains a **data dictionary**, explaining the name and meaning of each variable included in the dataset.

### Sheet 4 — Project Information

This sheet includes:

- Project description  
- Author information  
- Funding information  

---

## Methodological Notes

N-Gram frequencies were collected manually using the **Google Books N-Gram Viewer**.

Searches were conducted using the **English corpus** and the individuals’ **full names**, typically as **Two-Grams** (e.g., “Marcel Duchamp”, “Andy Warhol”, “Peggy Guggenheim”).

When necessary, additional queries were performed to resolve ambiguities related to **homonyms or common names**.

---

## Error Detection and Data Cleaning

The Google Books N-Gram corpus occasionally produces **temporal inconsistencies** or **false positives**.

For example:

The platform returns a frequency for the expression *“Andy Warhol”* in **1919**, although Andy Warhol was born in **1928**. This case was classified as an error.

Each case was manually investigated. Errors generally fell into three categories:

1. **Common names** producing ambiguous results (e.g., “Carolyn Brown”)  
2. **Homonymous individuals** (e.g., the painter Max Weber and the sociologist Max Weber)  
3. **Incorrect metadata in the Google Books corpus** (e.g., books with misdated publication years)

If errors were **systematic**, the individual was excluded from the dataset (`Utilizar? = Não`).  
If errors were **rare or clearly due to isolated cataloging issues**, the observations were retained.

---

## Representation of N-Gram Values

To facilitate computational processing, each N-Gram frequency value was decomposed into two components:

1. **Number of leading zeros**
2. **Significant digits**

For example: # N-Gram Dataset: Marcel Duchamp Social Network

**Author:** Felipe Braga  
**Related project:** Marcel Duchamp Ego Network Dataset  
**Source:** Google Books N-Gram Viewer (English Corpus)  
**License:** Creative Commons Attribution 4.0 International (CC-BY 4.0)

---

## Description

This dataset compiles **Google Books N-Gram frequencies** for the **434 individuals** who form the documented social network of the Franco-American artist Marcel Duchamp (Braga, 2023).

The dataset was constructed using the **Google Books N-Gram Viewer**, a platform that measures the frequency with which words, expressions, or phrases appear in a large corpus of digitized books from the Google Books project.

For example, when a user searches for the expression *"Marcel Duchamp"* in the N-Gram Viewer, the platform calculates the proportion of **Two-Grams** in the selected corpus that correspond to this expression. In 2022, approximately **0.0000165233%** of all Two-Grams in the corpus corresponded to the expression “Marcel Duchamp”.

The goal of this dataset is to provide **longitudinal indicators of cultural visibility** for the individuals documented in Duchamp’s social network.

---

## Dataset Structure

The dataset is distributed as a **Microsoft Excel (.xlsx) file** with four sheets:

### Sheet 1 — Node Variables and N-Gram Data

This sheet contains:

- Sociodemographic attributes of each node
- N-Gram frequency measurements
- Variables derived from the frequency values

Each row corresponds to **one individual in the Duchamp network**.

### Sheet 2 — Introduction to Google N-Grams

This sheet provides a **brief methodological explanation** of the Google Books N-Gram Viewer and the principles behind the frequency calculations.

### Sheet 3 — Variable Dictionary

This sheet contains a **data dictionary**, explaining the name and meaning of each variable included in the dataset.

### Sheet 4 — Project Information

This sheet includes:

- Project description  
- Author information  
- Funding information  

---

## Methodological Notes

N-Gram frequencies were collected manually using the **Google Books N-Gram Viewer**.

Searches were conducted using the **English corpus** and the individuals’ **full names**, typically as **Two-Grams** (e.g., “Marcel Duchamp”, “Andy Warhol”, “Peggy Guggenheim”).

When necessary, additional queries were performed to resolve ambiguities related to **homonyms or common names**.

---

## Error Detection and Data Cleaning

The Google Books N-Gram corpus occasionally produces **temporal inconsistencies** or **false positives**.

For example:

The platform returns a frequency for the expression *“Andy Warhol”* in **1919**, although Andy Warhol was born in **1928**. This case was classified as an error.

Each case was manually investigated. Errors generally fell into three categories:

1. **Common names** producing ambiguous results (e.g., “Carolyn Brown”)  
2. **Homonymous individuals** (e.g., the painter Max Weber and the sociologist Max Weber)  
3. **Incorrect metadata in the Google Books corpus** (e.g., books with misdated publication years)

If errors were **systematic**, the individual was excluded from the dataset (`Utilizar? = Não`).  
If errors were **rare or clearly due to isolated cataloging issues**, the observations were retained.

---

## Representation of N-Gram Values

To facilitate computational processing, each N-Gram frequency value was decomposed into two components:

1. **Number of leading zeros**
2. **Significant digits**

For example: 0.0000165233


is represented as:

- `zeros = 4`
- `significant_digits = 165233`

This transformation avoids problems related to **floating-point precision** and allows easier manipulation of extremely small frequency values.

---

## Related Dataset

This dataset complements the repository:

**Marcel Duchamp Ego Network Dataset**

Which documents **436 nodes and 5226 interactions** derived from archival sources related to Marcel Duchamp’s social network.

---

## Citation

If you use this dataset, please cite:

Braga, Felipe Eduardo Lázaro Braga. 2026.  
Marcel Duchamp Social Network N-Gram Dataset.

---

## License

This dataset is distributed under the **Creative Commons Attribution 4.0 International License (CC-BY 4.0)**.

You are free to:

- **Share** — copy and redistribute the material in any medium or format  
- **Adapt** — remix, transform, and build upon the material for any purpose  

Under the following condition:

- **Attribution** — appropriate credit must be given to the original author.


