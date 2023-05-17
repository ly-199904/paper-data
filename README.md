# paper-data
The simulation and analytical results for the submitted paper.

We provide two additional datasets, which include the raw simulation data, and the fitted BLER-SNR curves with their model parameters.

Some necessary explanations about the simulations are needed. Firstly, our simulations are conducted for different modulation and channel coding schemes (MCSs) with different blocklengths, we obtain a total of 106 combinations of MCSs and blocklengths for simulations. Then, the number of resource blocks (RBs), which are the smallest resource units, is set to be 1, 2, 4, 8, 16, 32, and 64, as specified in Section II of this paper, and we present the results for all MCSs under a certain RB value in a single figure or table. Additionally, the following results are generated with the selection of Kb based on performance, which is a crucial parameter as elaborated in Section III-A of this paper.

The first dataset contains the raw simulation data, which is obtained by performing link-level simulations based on the system model, as depicted in Fig. 1 of this paper. The tables record the block error rates (BLERs) for each MCS and each blocklength at different SNRs, SNRs are set with an interval of 0.5 dB.

The second dataset comprises the fitted BLER-SNR curves along with their model parameters, which is obtained by BLER~SNR performance fitting, as illustrated in Section III-B of this paper. The figures display the results of the fitting process, where the marks are simulation results and the lines are the fitting results. The tables list all the parameters of model (2).

The specific meanings of parameters in the figures and tables are explained in the corresponding sections of this paper, and will not be restated here.