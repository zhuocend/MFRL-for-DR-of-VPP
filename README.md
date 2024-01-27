## The project of paper "Massive Coordination of Distributed Energy Resource in VPP: A DRL based Multi-stage Optimization Approach"

This work proposed a efficient RL-based approach for coordinate demand response for massive distributed energy resources (DER) in VPP.

Using the following to obtain the project:
```git clone https://github.com/zhuocend/MFRL_DR_VPP.git```
### Updates, Jan/25/2024:
The used datasets in this work are updated.
Because it is difficult to obtain real operation data from VPPs, whereas the operation data of DERs are available, in this work, data from multiple open datasets containing PV outputs, the BSS demand, the real-time electricity price, etc., are used to generate the datasets required for each experimental scenario.

The raw data used for generation comes from the following sources:
- Base electrical load and thermal load: [ASU.Campus metabolism](http://cm.asu.edu/)
- Battery swap staion demand (bettery demand of EVs): [ACN-Data](https://ev.caltech.edu/dataset) [1]
- PV generation: [DKASC](https://dkasolarcentre.com.au/)
- Real time electricity price: [NYISO](http://mis.nyiso.com/public/)

We would like to thank the above projects and institutions for facilitating this work.

[1] Z. J. Lee, T. Li, and S. H. Low, “ACN-data: Analysis and applications of an open EV charging dataset” in Proceedings of the Tenth ACM International Conference on Future Energy Systems, 2019, pp. 139–149.

### Upcoming Updates:
- The parameter list of DERs and optimization models
- Data dictionary
- Source code (The author may not have permission to open source all the code, but at least Env will be provided so that other researchers can easily test their agents.)
