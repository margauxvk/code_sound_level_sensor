In this Github the Matlab code used for analyzing the simulation results and measurement results is given as well as the code for creating signals for measurements or simulations.

In the file *'transferfunction_exponential_sweep.m'* the transferfunction of the A-weighting circuit is calculated out of the exponential sweep measurements.\
To run the code *'transferfunction_exponential_sweep.m'* the following files are used:
1. The two wav files with the recordings of the measurement of the A-weighting circuit:
   - *'exponential_sweep_0tot20k_take2_in.wav'* 
   - *'exponential_sweep_0tot20k_take2_out.wav'*
2. The two wav files with the simulation results of the exponential sweep of the A-weighting circuit:
   - *'expsweep_30s_0tot20k.wav'*
   - *'exportexpsweep_30s_0tot20k.wav'*
3. The excel sheet with the simulation results of the linear sweep of the A-weighting circuit:
   - *'lin_sweep_20tot20k'*
4. The excel sheet with the calculated standard A-weighting values:
   - *'standardA_0tot20k'*

In the file *'Aweighting_transferfunction.m'* the transferfunction of the A-weighting circuit in the Laplace domain is calculted.

In the file *'creation_burst_signal.m'* the code for creating the burst signals using a Tukey window is written.

In the file *'generation_exponential_sweep.m'* the code for creating the exponential sweep is written.

    
