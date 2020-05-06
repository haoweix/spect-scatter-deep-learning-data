README

------

### Introduction:

This is Python data for (re)producing the results in the paper  
"A deep neural network for fast and accurate scatter estimation in quantitative SPECT/CT under challenging scatter conditions,"  
Haowei Xiang, Hongki Lim, Jeffrey A. Fessler, Yuni K. Dewaraja, 2020  
[todo: add link to the paper (after online link is available)]  
Published in
European Journal of Nuclear Medicine (EJNM)



### Content:

- This repository store phantom data, including training data and testing data:
  - ```training_data```: There are 8 simulations in training data and they are evenly seperated into 2 sets (s1 means set No.1 and s2 means set No.2). Each simluation consist of scatter, primary, total and also attenuation map (mu-map). 
  - ```test_data```: There are 6 instances of test data. 
    - ```cat_cali_measure_0822.mat```: measuement of 'calibration' phantom.
    - ```cat_liver_measure_w_noise_0826.mat```: measuement of 'liver' phantom.
    - ```cat_liver_w_noise_Apr2019.mat```: Monte Carlo simulation of 'liver' phantom.
    - ```cat_nema_w_noise_Apr2019.mat```: Monte Carlo simulation of 'NEMA' phantom.
    - ```cat_shell_measure_Aug2019.mat```: First measuement of 'shell' phantom (2 layers of activity).
    - ```cat_shell2_measure_08202019.mat```: Second measuement of 'shell' phantom (3 layers of activity).
- According to rule of sharing real patient data, real patient data is available on [<https://doi.org/10.7302/v07v-z854>].

