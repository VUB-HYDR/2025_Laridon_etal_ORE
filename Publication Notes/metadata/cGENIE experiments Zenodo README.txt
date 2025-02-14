Five AMOC sensitivity experiments were performed using the cGENIE model for the Laridon et al. (2025) paper in Open Research Europe:

1. Equilibrium of the AMOC under pre-industrial conditions:

This is a 15,000-year simulation with a fixed CO₂ concentration of 280 ppm and no freshwater forcing. The final state of the AMOC from this simulation is used as the initial condition for the subsequent sensitivity experiments. This experiment is referred to as JG.worjh2.main_eq.SPIN in the directory.

2. Bifurcation experiment of the AMOC with linear CO₂ forcing:

This experiment uses a linear CO₂ forcing over 20,000 years, with concentrations increasing from 280 ppm to 2800 ppm in the atmosphere. This calibration experiment is identified as EXPA in Laridon et al. (2025) and JG.worjh2.T_collapse.SPIN in the directory.

3. Bifurcation experiment of the AMOC with freshwater forcing and constant CO₂ forcing:

In this experiment, freshwater forcing is added linearly from 0 Sv to 0.2 Sv over 20,000 years, while CO₂ remains constant. The freshwater is applied between 50°N–70°N and 45°W–5°E, with constant global ocean salinity. This calibration experiment is referred to as EXPB in Laridon et al. (2025) and JG.worjh2.fw_collapse.SPIN in the directory.

4. AMOC timescale sensitivity experiment:

Freshwater flux is applied in the same region as in the previous experiment, using a stepwise parameterized forcing. The forcing begins at 0 Sv for 2000 years, then increases by 0.05 Sv to reduce AMOC intensity before returning to 0 Sv. This procedure is repeated after 6000 years, with the freshwater flux decreased by 0.05 Sv. This calibration experiment is referred to as EXPC in Laridon et al. (2025) and JG.worjh2.fw_zigzag.SPIN in the directory.

5. Bifurcation experiment of the AMOC with combined freshwater and CO₂ forcing:
    
This experiment combines the forcings from EXPA and EXPB over a 20,000-year simulation. It serves as a validation experiment, referred to as val_exp_1 in Laridon et al. (2025) and JG.worjh2.hybrid_collapse.SPIN in the directory.