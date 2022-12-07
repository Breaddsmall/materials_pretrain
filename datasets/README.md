# Benchmark datasets for pre-training model on crystalline material graphs

This directory contains five datasets as benchmark datasets for the pre-training task on crystalline material graphs. These datasets come from three sources based on Density Functional Theory (DFT) calculations.

The datasets are retrieved from `matminer.datasets` (Ward et al., 2018), and then further preprocessed. Training, testing and validation sets are randomly divided by the ratio of 6:2:2.
## Overwiew

### **[MP-2018](mp_2018)** and **[MP-2018-elastic](mp_2018_elastic)** (Jain et al., 2013) 

`MP-2018` contains ...[Details](mp_2018/README.md).

`MP-2018-elastic` is a subset of `MP-2018`, which contains ...[Details](mp_2018_elastic/README.md).

### **[JARVIS-DFT-3D](jarvis_dft_3d)** and **[JARVIS-DFT-3D-elastic](jarvis_dft_3d_elastic)** (choudhary & https://orcid.org/0000-0001-9737-8074, 2018; Choudhary et al., 2018)

`JARVIS-DFT-3D` contains ...[Details](jarvis_dft_3d/README.md).

`JARVIS-DFT-3D-elastic` is a subset of `JARVIS-DFT-3D`, which contains ... [Details](jarvis_dft_3d_elastic/README.md).

### **[Castelli-perovskites](perov)** (Castelli et al., 2012)

`Castelli-perovskites` contains ...[Details](perov/README.md).

## Citations

- `Matminer`
```
 @article{Ward_Dunn_Faghaninia_Zimmermann_Bajaj_Wang_Montoya_Chen_Bystrom_Dylla_et al._2018, title={Matminer: An open source toolkit for materials data mining}, volume={152}, ISSN={0927-0256}, DOI={10.1016/j.commatsci.2018.05.018}, journal={Computational Materials Science}, author={Ward, Logan and Dunn, Alexander and Faghaninia, Alireza and Zimmermann, Nils E. R. and Bajaj, Saurabh and Wang, Qi and Montoya, Joseph and Chen, Jiming and Bystrom, Kyle and Dylla, Maxwell and Chard, Kyle and Asta, Mark and Persson, Kristin A. and Snyder, G. Jeffrey and Foster, Ian and Jain, Anubhav}, year={2018}, month={Sep}, pages={60–69}, language={en} }
```

- `MP-2018` and `MP-2018-elastic`
```
@article{Jain2013, author = {Jain, Anubhav and Ong, Shyue Ping and Hautier, Geoffroy and Chen, Wei and Richards, William Davidson and Dacek, Stephen and Cholia, Shreyas and Gunter, Dan and Skinner, David and Ceder, Gerbrand and Persson, Kristin a.}, doi = {10.1063/1.4812323}, issn = {2166532X}, journal = {APL Materials}, number = {1}, pages = {011002}, title = {{The Materials Project: A materials genome approach to accelerating materials innovation}}, url = {http://link.aip.org/link/AMPADS/v1/i1/p011002/s1\&Agg=doi}, volume = {1}, year = {2013} }
```
- `JARVIS-DFT-3D` and `JARVIS-DFT-3D-elastic`
```
@article{PhysRevB.98.014107, title = {Elastic properties of bulk and low-dimensional materials using van der Waals density functional}, author = {Choudhary, Kamal and Cheon, Gowoon and Reed, Evan and Tavazza, Francesca}, journal = {Phys. Rev. B}, volume = {98}, issue = {1}, pages = {014107}, numpages = {12}, year = {2018}, month = {Jul}, publisher = {American Physical Society}, doi = {10.1103/PhysRevB.98.014107}, url = {https://link.aps.org/doi/10.1103/PhysRevB.98.014107} }

@misc{choudhary__2018, title={jdft_3d.json}, url={https://figshare.com/articles/jdft_3d-7-7-2018_json/6815699/2}, DOI={10.6084/m9.figshare.6815699.v2}, abstractNote={https://jarvis.nist.gov/ The Density functional theory section of JARVIS (JARVIS-DFT) consists of thousands of VASP based calculations for 3D-bulk, single layer (2D), nanowire (1D) and molecular (0D) systems. Most of the calculations are carried out with optB88vDW functional. JARVIS-DFT includes materials data such as: energetics, diffraction pattern, radial distribution function, band-structure, density of states, carrier effective mass, temperature and carrier concentration dependent thermoelectric properties, elastic constants and gamma-point phonons.}, publisher={figshare}, author={choudhary, kamal and https://orcid.org/0000-0001-9737-8074}, year={2018}, month={Jul}}
```
- `Castelli-perovskites`
```
@Article{C2EE22341D, author ="Castelli, Ivano E. and Landis, David D. and Thygesen, Kristian S. and Dahl, Søren and Chorkendorff, Ib and Jaramillo, Thomas F. and Jacobsen, Karsten W.", title  ="New cubic perovskites for one- and two-photon water splitting using the computational materials repository", journal  ="Energy Environ. Sci.", year  ="2012", volume  ="5", issue  ="10", pages  ="9034-9043", publisher  ="The Royal Society of Chemistry", doi  ="10.1039/C2EE22341D", url  ="http://dx.doi.org/10.1039/C2EE22341D", abstract  ="A new efficient photoelectrochemical cell (PEC) is one of the possible solutions to the energy and climate problems of our time. Such a device requires development of new semiconducting materials with tailored properties with respect to stability and light absorption. Here we perform computational screening of around 19 000 oxides{,} oxynitrides{,} oxysulfides{,} oxyfluorides{,} and oxyfluoronitrides in the cubic perovskite structure with PEC applications in mind. We address three main applications: light absorbers for one- and two-photon water splitting and high-stability transparent shields to protect against corrosion. We end up with 20{,} 12{,} and 15 different combinations of oxides{,} oxynitrides and oxyfluorides{,} respectively{,} inviting further experimental investigation."}
```