## Dataset Description

This repository contains the **raw data** associated with the publication:

**Utta, A.C.S., Oliveira, A.H.C., Souza, J.L.P., Fernandes, I.O., Magnusson, W.E., & Baccaro, F.B.**  
*High species turnover but functional stability in tropical ground-dwelling ant assemblages over twelve years of monitoring in Central Amazonia*  
(Accepted for publication in Insect Conservation and Diversity)

---

### Study Overview

This dataset results from a **12-year long-term ecological monitoring project** of **ground-dwelling ant assemblages** in a terra-firme tropical rainforest in **Reserva Florestal Adolpho Ducke**, near Manaus, Brazil. The study investigates taxonomic and functional dynamics of ant communities sampled in four years: **2006**, **2012**, **2014**, and **2018**.

---

### Study Location

- **Reserva Ducke**, Manaus, Brazil
- Coordinates: *Approx. 2°57' S, 59°56' W*
- Part of the Brazilian Long-Term Ecological Research Program (PELD/PPBio)

---

### Sampling Design

- **Sampling area**: 25 km² in Central Amazonia (Ducke Reserve)
- **Plots**: 30 permanent 250 m plots, spaced 1 km apart
- **Method**: Pitfall traps (10 traps per plot, 300 traps per year)
- **Seasons**: All sampling occurred during the dry season (Sept–Oct)
- **Years sampled**: 2006, 2012, 2014, 2018
- **Samples per year**: 300, totaling 1,200 samples

---

### Data Content

The data in this repository include:

- **Ant species occurrences** (presence in each trap)
- **Species abundance proxies** (number of workers sampled in each plot)
- **Taxonomic classification**: Subfamily, genus, species (including standardized morphospecies)
- **Functional group assignments**: Based on Groc et al. (2014) paper
- **Environmental descriptors**:
  - **Slope**: Terrain inclination per plot
  - **HAND**: Height above nearest drainage (proxy for water-table depth)

---

### File Structure

The CSV file contains:
- `YEAR`: Sampling year
- `SAMPLING_UNIT`: Plot ID
- `TAXON`: Full species or morphospecies name
- `N. OF WORKERS`: Proxy for abundance (number of pitfalls where the species was present)
- `FUNCTIONAL GROUP`: Assigned ecological function
- `HAND` and `Slope` values (in separated file)

---


### Citation and Contact

**If you use this dataset, please cite the original study**  
For questions, contact the corresponding authors:  
*uttaacsu18@gmail.com* or *baccaro@ufam.edu.br*
