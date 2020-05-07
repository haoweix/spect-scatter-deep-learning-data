README

------

### Introduction:

Data for (re)producing the results in the paper  
"A deep neural network for fast and accurate scatter estimation in quantitative SPECT/CT under challenging scatter conditions,"  
Haowei Xiang, Hongki Lim, Jeffrey A. Fessler, Yuni K. Dewaraja, 2020  
http://doi.org/10.1007/s00259-020-04840-9
Published in
European Journal of Nuclear Medicine (EJNM)

The corresponding Python code is available at
https://github.com/haoweix/spect-scatter-deep-learning

### Content:

- This repository stores phantom SPECT projection view data,
including training data and testing data:
  - ```training_data```: contains 8 sets of simulations that are evenly seperated into 2 sets
  (s1 means set No.1 and s2 means set No.2).
  Each simulation consists of scatter, primary, total projection views, and also attenuation map (mu-map). 
  - ```test_data```: contains 6 test data sets. 
    - ```cat_cali_measure_0822.mat```: measuement of 'calibration' phantom.
    - ```cat_liver_measure_w_noise_0826.mat```: measuement of 'liver' phantom.
    - ```cat_liver_w_noise_Apr2019.mat```: Monte Carlo simulation of 'liver' phantom.
    - ```cat_nema_w_noise_Apr2019.mat```: Monte Carlo simulation of 'NEMA' phantom.
    - ```cat_shell_measure_Aug2019.mat```: First measuement of 'shell' phantom (2 layers of activity).
    - ```cat_shell2_measure_08202019.mat```: Second measuement of 'shell' phantom (3 layers of activity).
- Per data sharing rules, real patient data is available at Deep Blue https://doi.org/10.7302/v07v-z854.

