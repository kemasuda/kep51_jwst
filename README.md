# kep51_jwst

[**A Fourth Planet in the Kepler-51 System Revealed by Transit Timing Variations** (Masuda, Libby-Roberts et al., 2024)]()

#### data/
Transit times in Table 1.

#### results/
Results of four-planet TTV modeling in Section 7 using [jnkepler](https://github.com/kemasuda/jnkepler).
The osculating orbital elemetns are defined at BJD=2454833+155. Files with names \*ttvfast\* include the parameters that are compatible with TTVFast.
  - grid_search/: solutions from brute-force searches in Section 7.1.
  - hmc/: posterior samples for the 2:1 solution in Section 7.3.
  
#### predictions/ 
Predicted transit times of Kepler-51b, c, and d in Table 7.
 
