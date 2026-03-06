# Marcel Duchamp Ego Network Dataset

## Description

The **marcel_duchamp_ego_network** dataset documents a social network reconstructed from primary sources related to the artist Marcel Duchamp.

The dataset contains **436 nodes and 5226 documented interactions**.

The dataset was compiled between **2021 and 2022** through the systematic examination of archival materials, correspondence, interviews, photographs, and published documentary sources.

The dataset represents an **ego network**, centered on Marcel Duchamp, and includes individuals who interacted with him as well as interactions between those individuals when such relationships were documented in the Duchamp archival corpus.

The dataset was produced as part of a research project funded by **FAPESP (São Paulo Research Foundation), grant nº 2021/00645-8**.

---

# Dataset Structure

The dataset consists of **three CSV files**.

## 1. Network Relations Matrix  
`marcel_duchamp_ego_network.csv`

**Size:** 238 KB  
**Rows:** 5226

This is the main edge list of the network.

### Variables

| Variable | Description |
|---|---|
| id_origem | Unique identifier of the source node |
| label_origem | Name of the source node |
| id_destino | Unique identifier of the destination node |
| label_destino | Name of the destination node |
| id_documento | Identifier of the primary document in which the interaction was recorded |

Relations represent **documented interactions** between individuals.

The network is **undirected**, meaning the interaction does not imply directionality.

---

## 2. Primary Documents Metadata  
`matriz_atributos_documentos_primarios.csv`

**Size:** 159 KB  
**Rows:** 957

This table contains metadata for the primary sources from which network relations were extracted.

### Variables

| Variable | Description |
|---|---|
| id_doc | Unique identifier of the document |
| type | Type of document (letter, interview, photograph, film, etc.) |
| name | General title or description of the document |
| place | Archive, collection, or publication where the document is stored |
| date | Date of production (format: YYYY/MM/DD) |
| link | Link to a digital version of the document, when available |

Examples of document repositories and publications include archival collections and documentary publications related to Duchamp.

---

## 3. Node Attributes Matrix  
`matriz_atributos_nodos.csv`

**Size:** 64 KB  
**Rows:** 436

This table contains attributes for the individuals present in the network.

### Variables

| Variable | Description |
|---|---|
| id_node | Unique node identifier |
| label_node | Name of the individual |
| gender_por / gender_eng / gender_fren | Gender recorded in Portuguese, English, and French |
| nationality_por / nationality_eng / nationality_fren | Nationality in Portuguese, English, and French |
| grave_country_por / grave_country_eng / grave_country_fren | Country where the individual is buried |
| occupation_por / occupation_eng / occupation_fren | Main occupation |
| year_birth | Year of birth |
| year_death | Year of death |

Some entries contain **NA values**, which correspond to individuals whose biographical information could not be reliably identified in available sources.

---

# Methodological Notes

Relations in the dataset represent **documented interactions identified in primary sources**. These interactions are not categorized by type (such as friendship, collaboration, or family relationship), but instead reflect the existence of documented contact or interaction between individuals.

---

# Limitations

This dataset does not aim to reconstruct the complete social network of Marcel Duchamp. Rather, it documents the network **as it emerges from the corpus of primary sources consulted during the research**.

The dataset is more robust in mapping relationships between **Marcel Duchamp (ego) and other individuals (alters)**.

Relationships **between alters themselves** are included **only when they appear explicitly in the Duchamp archival corpus**. As a result, the alter–alter portion of the network contains gaps.

A fully exhaustive reconstruction of alter–alter relationships would require systematically investigating whether each of the **434 alters** had connections with the other **433 individuals**, which would make the project practically unfeasible and significantly delay the publication of the dataset.

---

# License

This dataset may be used freely for research and educational purposes, provided that the dataset is properly cited.

---

## Citation

If you use this dataset, please cite:

Braga, Felipe Eduardo Lázaro. 2026.  
Marcel Duchamp Ego Network Dataset.

Funded by **FAPESP – Grant nº 2021/00645-8**.