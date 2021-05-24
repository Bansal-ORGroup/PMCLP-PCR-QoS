# PMCLP-PCR-QoS
This is the companion repository for [our paper](https://lnkd.in/geciVDj) titled "Planar Maximum Coverage Location Problem with Partial Coverage, Continuous Spatial Demand, and Adjustable Quality of Service" which is available on [ArXiv](https://lnkd.in/geciVDj). 
In this paper, we consider a generalization of the classical planar maximum coverage location problem (PMCLP) in which partial coverage is allowed, facilities have adjustable quality of service (QoS) or service range, and demand zones and service zone of each facility are represented by two-dimensional spatial objects.  We denote this generalization with rectangular spatial objects by PMCLP-PCR-QoS which has applications in camera surveillance and satellite imaging. A key challenge in this problem is to simultaneously decide position of multiple facilities on a continuous two-dimensional plane and their QoS. In this paper, we present a greedy algorithm and a pseudo-greedy algorithm for it, and provide their approximation ratios. We also investigate theoretical properties and propose exact algorithms for solving PMCLP-PCR-QoS. (Abstract of the paper)

<img src="PMCLP-PCR-QoS.gif" alt="An example of PMCLP-PCR-QoS with 20 rectangular demand zones (represented with black outline) and 3 rectangular service zones for facilities (represented with red)." width="800" height="500">

## Citation
If you use this dataset in a publication, a link to or citation of this paper would be appreciated

Manish Bansal, Parshin Shojaee. "Planar Maximum Coverage Location Problem with Partial Coverage, Continuous Spatial Demand, and Adjustable Quality of Service" 2020.
[arXiv:2012.09063.1](https://lnkd.in/geciVDj)

```ruby
@misc{bansal2020planar,
      title={Planar Maximum Coverage Location Problem with Partial Coverage, Continuous Spatial Demand, and Adjustable Quality of Service}, 
      author={Manish Bansal and Parshin Shojaee},
      year={2020},
      eprint={2012.09063},
      archivePrefix={arXiv},
      primaryClass={math.OC}
}
```

## Data
The data used in this project is provided in the [Data](https://github.com/Bansal-ORGroup/PMCLP-PCR-QoS/tree/main/Data) folder. This folder consists of four sub-folders for samples with [10](https://github.com/Bansal-ORGroup/PMCLP-PCR-QoS/tree/main/Data/10DZs), [25](https://github.com/Bansal-ORGroup/PMCLP-PCR-QoS/tree/main/Data/25DZs), [50](https://github.com/Bansal-ORGroup/PMCLP-PCR-QoS/tree/main/Data/50DZs), and [100](https://github.com/Bansal-ORGroup/PMCLP-PCR-QoS/tree/main/Data/100DZs) number of rectangular demand zones (DZs). Each folder contains 10 data samples.
