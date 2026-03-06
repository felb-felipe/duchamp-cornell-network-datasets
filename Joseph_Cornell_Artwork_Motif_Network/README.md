# Joseph Cornell Artwork Motif Network

**Author:** Felipe Eduardo Lázaro Braga  
**Project:** Material Networks in Modern Art  
**Funding:** FAPESP – Fundação de Amparo à Pesquisa do Estado de São Paulo

---

## Description

This dataset maps **poetic motifs across the object-based artworks of Joseph Cornell**.

The dataset contains **166 artworks** produced by the American artist Joseph Cornell, who began working with found objects in the early 1930s and continued exploring this artistic support for approximately four decades.

The goal of the dataset is to investigate the **evolution and internal structure of Cornell’s artistic language** by analyzing how recurring poetic elements appear across his artworks.

Instead of studying each artwork in isolation, the dataset models Cornell’s production as a **network of relations between artworks mediated by shared motifs**.

---

## Methodology

The dataset was constructed through a **qualitative visual analysis of artworks** documented in museum collections.

A corpus of **166 artworks created with real objects** was assembled. Each artwork was analyzed using the qualitative analysis software *FreeMind*, where photographs of the works were annotated to identify the **poetic elements composing each piece**.

Examples of these elements include:

- boxes  
- birds  
- glass goblets  
- celestial tables  
- shells  
- pipes  
- spirals  
- wooden fragments  
- collages  

After reviewing the entire corpus, **29 recurring motifs** were identified as structuring components of Cornell’s poetic vocabulary.

---

## Data Structure

The dataset is organized as a **rectangular matrix**:

- **Rows:** artworks (166)  
- **Columns:** motifs (29)

Each cell contains:

- **1** → the motif is present in the artwork  
- **0** → the motif is absent

Through this structure, the dataset produces a **network of relationships between artworks**, where two artworks are connected when they share one or more motifs.

---

## Motifs Identified

The dataset contains the following **29 poetic motifs**:

Esfera  
Caixa  
Argolas  
Trilho  
Taça  
Taça_quebrada  
Desenho/Fotografia  
Cachimbo  
Tabela_astronômica  
Palavras  
Caixa_dentro_da_caixa  
Pássaro  
Concha  
Pedaços_de_madeira  
Colagem  
Espiral  
Gradil/Compartimentação  
Gaveta  
Relógio/Bússola  
Hotel  
Areia  
Pilar  
Grade_de_arame  
Médici  
Frascos  
Dispensador_de_areia  
Boneca  
Cubos_de_vidro  
Folhas/pétalas

---

## Analytical Possibilities

This structure allows researchers to investigate:

- **the most frequent motifs** in Cornell’s work  
- **motifs that connect multiple artistic series**  
- **clusters of artworks sharing similar poetic structures**  
- **the evolution of Cornell’s visual language over time**

Because each artwork includes production dates, the network can also be analyzed **diachronically**, allowing comparisons between different decades of the artist’s career.

---

## Artwork Metadata

Each artwork includes the following attributes:

- **id** – unique identifier  
- **artwork_title** – name of the artwork  
- **start_year** – year in which production began  
- **end_year** – year of completion  

---

## Citation

If you use this dataset, please cite:

Braga, Felipe Eduardo Lázaro. 2026.  
Joseph Cornell Artwork Motif Network Dataset.

---

## License

This dataset is released under a **permissive license**.  
Reuse, redistribution, and adaptation are allowed **provided that the original authorship is properly cited**.