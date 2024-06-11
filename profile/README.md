# This project is completed as a partial requirement for the Master's capstone project at the Bren School of Environmental Science and Management at the University of California, Santa Barbara

## Introduction
Scientists at the National Center for Atmospheric Research have recently carried out several experiments to better understand the uncertainties associated with future climate projections. In particular, the NCAR Climate and Global Dynamics Lab (CGDL) working group has completed a large Parameter Perturbation Experiment (PPE) utilizing the Community Land Model (CLM), testing the effects of 32 parameters over thousands of simulations over a range of 250 years. The CLM model experiment is focused on understanding uncertainty around biogeophysical parameters that influence the balance of chemical cycling and sequestration variables. The current website for displaying model results is not intuitive or informative to the broader scientific audience or the general public. The goal of this project is to develop an improved data visualization dashboard for communicating the results of the CLM PPE. The interactive dashboard would provide an interface where new or experienced users can query the experiment database to ask which environmental processes are affected by a given model parameter, or vice versa. Improving the accessibility of the data will allow professionals to use the most recent land parameter data when evaluating the impact of a policy or action on climate change. 

#### Project Link
https://bren.ucsb.edu/projects/understanding-influence-parameter-value-uncertainty-climate-model-output-developing
#### Link to Client website: National Center for Atmospheric Research
https://ncar.ucar.edu/

## Description of the Repositories
Prototype: Contains cleaned version of the codes on Machine Learning and non-Dashboard stuffs
CLM5_PPE_Emulator: Contains the clean codes for Dashboard creation and testing of Dashboard on private network NCAR's server
GaiFuture: Contains the unclean codes. These are mostly practices the team performed during the start of the project to better gain idea about project.

## Project title
Understanding the Influence of Parameter Value Uncertainty on Climate Model Output: Developing an Interactive Dashboard

## Futher Information

**Principal Investigator:** Daniel Kennedy  
**Project Team:** Sujan, Sofia, Heather  
**Contact Information:**  
- **Principal Investigator:** Daniel Kennedy  
  - **Email:** djk2120@ucar.edu  
  - **Affiliation:** National Center For Atmospheric Research @ UCSB  

**Date of Data Collection:** August 2023  
**Methodology:** Using the Community Land Model (version 5.2) on NSF-NCAR's Cheyenne supercomputer

**Geographic Location:** Global coverage

**Funding:**  
The CESM project is primarily supported by the National Science Foundation (NSF). This work is based on NSF support under Cooperative Agreement 1852977. Computing and data storage resources, including the Cheyenne supercomputer (doi: 10.5065/D6RX99HX), were provided by the Computational and Information Systems Laboratory (CISL) at NSF-NCAR.

## Sharing/Access Information

**Licenses/Restrictions:** No restrictions as of May 20, 2024

**Publications:**
- [CLM5PPE GitHub Repository](https://github.com/djk2120/clm5ppe)

**Publicly Accessible Data Locations:**  
Privately owned under the UCAR platform. Data is not available on other platforms as of May 20, 2024.

**Ancillary Data Sets:** None

**Derived Data:** Data owned by the principal investigator

**Citation:**
- Lawrence, D. M. et al. (2019). The Community Land Model version 5: Description of new features, benchmarking, and impact of forcing uncertainty. Journal of Advances in Modeling Earth Systems, 11, 4245–4287. https://doi.org/10.1029/2018MS001583

## Data & File Overview

**File List:**
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0004.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0005.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0006.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0007.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0008.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0009.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0010.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0011.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0012.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0013.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0014.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0015.clm2.h0.2005-02-01-00000.nc`
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0016.clm2.h0.2005-02-01-00000.nc`
- .......................
- .......................
- .......................
- `/glade/campaign/cgd/tss/projects/PPE/PPEn11_LHC/transient/hist/PPEn11_transient_LHC0500.clm2.h0.2005-02-01-00000.nc`

**Relationship Between Files:** All data are independent, but the condition on each experiment run is the same.

**Additional Related Data:** All other data collected are privately owned by the author and not available for disclosure.

**Multiple Versions:** No multiple versions. Single version run in 2023.

## Methodological Information

**Description of Methods:**  
CLM5 development has prioritized improved understanding of carbon and nitrogen cycle interactions and their influence on the long-term trajectory of the terrestrial carbon sink using community-based land models. These objectives are pursued through a combination of model parameterization refinement, process-based simulations, and validation against empirical data. Specifically, CLM5 incorporates advanced algorithms and updated parameter sets to better capture the complexities of carbon and nitrogen cycling within terrestrial ecosystems. Furthermore, model simulations are validated against observational data and experimental studies to assess the model's performance in representing carbon and nitrogen dynamics under varying environmental conditions and management practices. Detailed information can be found in:

- Lawrence, D. M. et al. (2019). The Community Land Model version 5: Description of new features, benchmarking, and impact of forcing uncertainty. Journal of Advances in Modeling Earth Systems, 11, 4245–4287. https://doi.org/10.1029/2018MS001583

**Methods for Processing Data:**  
32 parameters were chosen to tune during the model creation. At each point, some random variables were tweaked, resulting in different outputs. This was based on the Sobol sampling approach. The data were simulated from 1995 to 2015 for 500 simulations. Each simulation produced values for 397 outputs.

**Instrument or Software Requirements:**  
Requires massive computing resources and can only be accessed from the supercomputer. Cluster requests from the supercomputer should ideally contain 40 cores with a minimum of 4GB RAM and 1 thread per core.

**Standards and Calibration Information:**
- Parameters were changed on the scale of 0 to 1
- Machine learning approach GPR was used to process the data
- Sobol sampling approach was taken for input variables

**Environmental/Experimental Conditions:**  
This is a climate simulation, so no specific condition was set, but the basic physical processes of the Earth were assumed true during the experiment.

**Quality Assurance Procedures:**  
This is a physically based method, replicating how the natural world interacts. Due to the lack of direct observed data from the field, the dataset was not assured with real-world data.

**People Involved:**  
Daniel Kennedy, Principal Investigator and Data Collector

## Data-Specific Information

**Filename Pattern:**  
There are 500 datasets in the following format:  
`PPEn11_transient_LHC[0][0-5][0-9][0-9].clm2.h0.2005-02-01-00000.nc`  
They all contain the output for the same variables and take in the same inputs.

**Input Variables:** 32  
**Output Variables:** 497

**Dimensions of Input Variables:**  
- Rows: 500
- Columns: 32

**Dimensions of Output Variables:**
- levgrnd: 25
- levsoi: 20
- levlak: 10
- levdcmp: 25
- time: 60
- hist_interval: 2
- lon: 144
- lat: 96
- gridcell: 400
- landunit: 1267
- column: 2974
- pft: 8574
- cft: 2
- ltype: 9
- nvegwcs: 4

**Variable List:**  
Refer to the [Splash Documentation Page](https://github.com/GaiaFuture/GaiaFuture/blob/main/Script/ML/gaussian/param.html). All input variables are scaled from 0 to 1, making them unitless.

**Missing Data Codes:**  
No missing data. The climate model output contains complete data with no NaN or incompatible values.

**Specialized Formats or Abbreviations:**  
NETCDF
