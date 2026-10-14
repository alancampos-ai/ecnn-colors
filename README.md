# Graphs Colors  

#### Article: <small><strong>Equivariant total colourings of regular graph-cycle products</strong> <a href=""><img src="https://cdn.simpleicons.org/doi/2dd4bf" alt="DOI" height="14" align="absmiddle"></a> <a href=""><img src="https://cdn.simpleicons.org/zenodo/2dd4bf" alt="Zenodo" height="14" align="absmiddle"></a> <a href="https://drive.google.com/drive/folders/1R9l6bUsQ59eoUDFF8O1g_qeNeTouwofn?usp=drive_link"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="Google Drive" height="14" align="absmiddle"></a></small>

We study optimal total colourings of $G\times C_m$ under prescribed colour permutations induced by cycle rotation. For nonempty $r$-regular $G$, when $r$ is even or $G$ has a $1$-factor, an equivariant unit-shift $(2r+1)$-colouring exists exactly when $(2r+1)\mid m$. In particular, $\chi_T(G(n,k)\times C_{7t})=7$ for generalized Petersen graphs and $t\geq1$. For $2$-regular graphs, all seven five-colour permutation types are classified; type $(4,1)$ is impossible. A $60$-state transition graph counts labelled colourings and supports output-optimal construction. EqShift is compared with PicoSAT and OR-Tools CP-SAT across $66$ construction and $14$ counting configurations, with full and reduced formulations, $20$ seeds, and $9{,}600$ executions. All three methods agree on feasibility and exact counts. On reduced $C_{40}\times C_{20}$, EqShift reaches $0.063359$ ms median algorithm time, a reduction of $98.14\%$ versus SAT and $99.78\%$ versus CP-SAT. Counting and whole-process rankings vary by configuration.

#### Dependencies

* Python 3.11
* NumPy 1.26.4
* SciPy 1.13.1
* Matplotlib 3.10.8
* NetworkX 3.4.2
* pycosat 0.6.6
* OR-Tools 9.6
* Protobuf 4.21.12
* PyYAML 6.0.2

#### Installation

```bash
docker compose -f docker/compose.yaml build
docker compose -f docker/compose.yaml run --rm main
```

#### License (MIT)

* Copyright (c) alancampos-ai
* Code released under the MIT License.
