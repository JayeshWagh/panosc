PaNOSC USE CASES
=========================================================

Use Case 1 – EuXFEL Data in NeXus Golden Standard (European XFEL)
=========================================================	
There were great efforts put in the last two decades in the research community to elaborate a common standard for high data-rate macromolecular crystallography (HDRMX). This agreed “Gold Standard” builds on the NeXus/HDF5 NXmx application definition and the International Union of Crystallography (IUCr) imgCIF/CBF dictionary, and it is compatible with major data-processing programmes and pipelines. Here we demonstrate the EuXFEL data packed into a NeXus file, which is fully compliant with the Gold Standard by design, since it is built directly from HDRMX NeXus definitions. We use open-source software developed both by community (cctbx) and in-house (extra-data).

Developers:
------	
Herbert Bernstein, Andreas Förster, Asmit Bhowmick, Aaron Brewster, Sandor Brockhauser, Luca Gelisio, David Hall, Filip Leonarski, Valerio Mariani, Gianluca Santoni, Clemens Vonrheink, Graeme Winter, Anton Barty, Thomas Kluyver, Fabio Dall’Antonias, Yury Kirienk

References:
------	
[1] Bernstein, H. J., Förster, A., Bhowmick, A., Brewster, A. S., Brockhauser, S., Gelisio, L., … & Winter, G. (2020). Gold Standard for macromolecular crystallography diffraction data. IUCrJ, 7(5), DOI: https://doi.org/10.1107/S2052252520008672

[2] CXI DB #80, DOI: https://dx.doi.org/10.11577/1464101

[3] A. Brewster, M. Wang, H. Bernstein. (2019). 68 image lysozyme dataset recorded on the Jungfrau 16M detector at SwissFEL and formatted as a NeXus file (Version 3) [Data set]. DOI: https://doi.org/10.5281/zenodo.3834335

PaNOSC related work packages:
------	
[WP3 – Data Catalog Services](https://www.panosc.eu/work-packages/work-package-3-data-catalog-services/)

Contact person:
------	
[Yury Kirienko](mailto:yury.kirienko@xfel.eu) (European XFEL)

More on PaNOSC github:
------	
https://github.com/European-XFEL-examples/panosc-nexus

LINK to website
------
https://www.panosc.eu/use-cases/use-case-1-euxfel-data-in-nexus-golden-standard/

------
Use Case 2 – Operation of X-ray gas monitors at the European XFEL (European XFEL)
=========================================================	
X-ray gas monitors (XGMs) are operated at the European XFEL for non-invasive single-shot pulse energy measurements and average beam position monitoring. They are used for tuning and maintaining the self-amplified spontaneous emission (SASE) operation and for sorting single-shot experimental data according to the pulse-resolved energy monitor data. The XGMs were developed at DESY based on the specific requirements for the European XFEL. In total, six XGM units are continuously in operation.

Here, the main principle and experimental setup of an XGM are summarized, and the locations of the six XGMs at the facility are shown. Pulse energy measurements at 0.134 nm wavelength are presented, exceeding 1 mJ obtained with an absolute measurement uncertainty of 7–10%; correlations between different XGMs are shown, from which a SASE1 beamline transmission of 97% is deduced. Additionally, simultaneous position measurements close to the undulator and at the end of the tunnel are shown, along with the correlation of beam position data simultaneously acquired by an XGM and an image.

Developers: 
------	
T. Maltezopoulos, F. Dietrich, W. Freund, U. F. Jastrow, A. Koch, J. Laksman, J. Liu, M. Planas, A. A. Sorokin, K.

Tiedtke and J. Grünert, R. Rosca

References:
------	
[1] J. Synchrotron Rad. (2019). 26, 1045-1051, DOI: doi.org/10.1107/S1600577519003795

PaNOSC related work packages:
------	
[WP4 – Data Analysis Services](https://www.panosc.eu/work-packages/work-package-4-data-analysis-services/)

Contact person:
------	
[Robert Rosca](mailto:robert.rosca@xfel.eu) (European XFEL)

More on PaNOSC github:
------	
https://github.com/European-XFEL-examples/jsr-operation-xgm-euxfel-paper

LINK to website:
------
https://www.panosc.eu/use-cases/use-case-2-operation-of-x-ray-gas-monitors-at-the-european-xfel/

------
Use Case 3 – Machine Learning Based Spectra Classification (European XFEL)
=========================================================

At the European XFEL, X-ray pulses can be generated with only 220ns separation in time and a maximum of 27000 pulses per second. In experiments at European XFEL, spectral changes can indicate the change of the system under investigation and so the progress of the experiment. An immediate feedback on the actual status (e.g., time resolved status of the sample) would be essential to quickly judge how to proceed with the experiment. The two major spectral changes that we aim to capture are either the change of intensity distribution (e.g., drop or appearance) of peaks at certain locations, or the shift of those on the spectrum.

Machine Learning (ML) opens up new avenues for data-driven analysis in spectroscopy by offering the possibility to quickly recognize such specific changes on-the-fly during data collection. ML requires lots of data which are clearly annotated. Hence, it is important that research outputs align with the FAIR principles. In case of XFEL experiments, it is suggested to introduce NeXus data format standards in future experiments.

In this work an example is presented, of a possible use of Neural Network based ML for accurately classifying the system state if data is properly provided. A solution is shown, to automatically find the regions (or bins) with high separability where the spectra classes differ significantly. By teaching individual neural networks for each bin, and by combining them with a weighting technique, a robust classification of any new spectral curve can be quickly obtained.

Developers:
------	
Christian Plueckthun; Zuzana Konopkova; Sandor Brockhauser; Yue Sun

References:
------	
[1]. Pennicard, D., Smoljanin, S., Pithan, F., Sarajlic, M., Rothkirch, A., Yu, Y., Liermann, H.P., Morgenroth, W., Winkler, B., Jenei, Z. and Stawitz, H., 2018. LAMBDA 2M GaAs—A multi-megapixel hard X-ray detector for synchrotrons. Journal of Instrumentation, 13(01), p.C01026, DOI: 10.1088/1748-0221/13/01/C01026

PaNOSC related work packages:
------	
[WP4 – Data Analysis Services](https://www.panosc.eu/work-packages/work-package-4-data-analysis-services/)

Contact person:
------	
[Yue Sun](mailto:yue.sun@xfel.eu) (European XFEL)

More on PaNOSC github:
------	
https://github.com/European-XFEL-examples/panosc-ml-spectra-classification

LINK to website:
------
https://www.panosc.eu/use-cases/use-case-3-machine-learning-based-spectra-classification/

------
Use Case 4 – SASE Pulse Delivery Analysis (European XFEL)
=========================================================

An analysis workflow implemented to a Jupyter notebook was used to look at XGM (X-ray Gas Monitor) data that was recorded in the same time interval, but in different parts of European XFEL. In essence, pulse energy (intensity) values from one XGM in SASE1 were compared to another set from an XGM in SASE3. This data stems from alternating X-ray pulses sent through one or the other tunnel and recorded separately. The aim was to determine the suppression rate for intensity from unwanted residual photons in each “non-pulse” time interval.

Conceptually and technically, this analysis makes use of the data-object xarray.DataArray within the EXtra-data framework and implements a simple form of error propagation. It is already public as example notebook in the EXtra-data documentation: https://extra-data.readthedocs.io/en/latest/xpd_examples2.html, and could be of value to PaNOSC due to its transferability to the general case of data comparison and/or error determination.

Developers:
------
Theophilos Maltezopoulos, Jan Grünert, Thomas Kluyver, Fabio Dall’Antonia

References:
------
[1] Tiedtke et al., Gas-detector for X-ray lasers , J. Appl. Phys. 103, 094511 (2008) – DOI 10.1063/1.2913328

[2] Sorokin et al., J. Synchrotron Rad. 26 (4), DOI 10.1107/S1600577519005174 (2019)

[3] Th. Maltezopoulos et al., J. Synchrotron Rad. 26 (4), DOI 10.1107/S1600577519003795 (2019)

PaNOSC related work packages:
------
[WP4 – Data Analysis Services](https://www.panosc.eu/work-packages/work-package-4-data-analysis-services/)

Contact person:
------
[Fabio Dall’Antonia](fabio.dall.antonia@xfel.eu) (European XFEL)

More on PaNOSC github:
------
https://github.com/European-XFEL-examples/panosc-sase-pulse-delivery-analysis

LINK to website:
------
https://www.panosc.eu/use-cases/use-case-4-sase-pulse-delivery-analysis/

------
Use Case 5 – Detector Calibration (European XFEL)
=========================================================

European XFEL uses a range of pixel detectors, including some which are custom built to cope with the high pulse rate. The raw data recorded from these detectors needs various corrections applied as a first step in analysing it.

The workflows for applying corrections and for creating the calibration constants they use are implemented in a collection of Jupyter notebooks.

Detector experts can conveniently work with a small amount of data to develop these notebooks interactively. A supporting software infrastructure runs the notebooks in parallel on the Maxwell cluster as new runs are saved, to create corrected data. The notebooks also generate plots and summary statistics to monitor the calibration quality, and the notebooks used for each run are converted into a PDF report saved alongside the data.

Developers:
------
M. Kuster, J.-S. Dambietz, S. Hauf, T. Kluyver, R. Rosca, Y. Kirienko

References:
------
[1] M. Kuster, D. Boukhelef, M. Donato, J.-S. Dambietz, S. Hauf, L. Maia, N. Raab, J. Szuba, M. Turcato, K. Wrona & C. Youngman (2014) Detectors and Calibration Concept for the European XFEL, Synchrotron Radiation News, 27:4, 35-38, DOI: 10.1080/08940886.2014.930809

[2] H. Fangohr, S. Brockhauser, et al. (2020) Data Exploration and Analysis with Jupyter Notebooks. Proc. ICALEPCS’19, 799—806. DOI:10.18429/JACoW-ICALEPCS2019-TUCPR02

PaNOSC related work packages:
------
[WP4 – Data Analysis Services](https://www.panosc.eu/work-packages/work-package-4-data-analysis-services/)

Contact person:
------
[Thomas Kluyver](mailto:thomas.kluyver@xfel.eu) (European XFEL)

More on PaNOSC github:
------
https://github.com/European-XFEL-examples/panosc-detector-calibration

LINK to website:
------
https://www.panosc.eu/use-cases/use-case-5-detector-calibration/

------
Use Case 6 – Analysing 2D uXRD maps for cultural heritage samples (ESRF)
=========================================================

Improving the efficiency of 2D uXRD experiments (many different users, a possible regular beamtime, remote experiment), would help to have a dedicated Jupyter notebook for data processing. It would be a good way:

*To save time;
*To record which map has already been processed and how;
*To have a coherent data processing between users and between sessions, and also for possible users who would like to reuse data after the embargo period.

Use Case Action Flow:
------
*Extract data
*Radial integration
*Combine maps

Impacts from the implementation:
------
The goal will be to perform 2D µXRD maps on painting fragments from various historical paintings in a reproducible and user friendly manner for non-expert synchrotron users.

Generalisation of the use case:
------
It could be useful for any 2D µXRD mapping experiments.

Partners:
------
All synchrotrons doing 2D µXRD mapping of heterogeneous samples e.g. Petra-II DESY, DIAMOND, ELETTRA, SOLEIL

Resources:
------
h5py, pyFAI, Jupyter notebooks

Source code >> https://gitlab.esrf.fr/loic.huder/id13_jupyter

PaNOSC related work packages:
------
[WP4 – Data Analysis Services](https://www.panosc.eu/work-packages/work-package-4-data-analysis-services/)

Contact person:
------
[Loïc Huder](mailto:loic.huder@esrf.fr) (ESRF)

LINK to website:
------
https://www.panosc.eu/use-cases/use-case-6-analysing-2d-uxrd-maps-for-cultural-heritage-samples/

------
Use Case 7 – Data Transfer using EGI-DataHub/Onedata (CERIC-ERIC)
=========================================================

Until recently, most Neutron and X-ray (Photon and Neutron also known as PaN) facility users had to use predominantly portable media to transfer data produced by the research infrastructure’s (RI) instruments to their home lab for analyses. This was the predominant model some years ago, when the volume of data was relatively low and compatible with the network, the storage and the compute capacity of the facility users’ organisations.

Nowadays, the volume of the raw data produced for a single experiment in a photon or neutron RI ranges from some hundreds of MB to 100 TB depending on the instrument technique. This 106-scale factor, associated with the large spectrum of scientific communities with very diverse practices makes it extremely difficult to propose a single model for the scientists that want to process data.

In this use case, a data transfer solution using EGI-DataHub/OneData is showcased, for users willing to analyse datasets produced during one of the experiments at a PaN RI, using the Jupyter Notebooks service in the EGI infrastructure.

Use case action flow
------
*Transfer data via EGI DataHub based on Onedata from an NFS storage located at CERIC-ERIC / Elettra RI to EGI infrastructure Data Analysis service
*Archive the results back to the originated RI
*Authenticate users using the EOSC ready PaN community AAI (UmbrellaID)

Impacts from the implementation
------
*ata transfer of up to 100 GB
*HDF5 data files >1GB can reach the maximum bandwidth available
*Smaller files have a much smaller throughputs (1/5)
*Files<50MB in size take the same amount of time of 250MB files, probably to the overhead required by the Onedata transfer protocol, a standard pattern of network file transfer protocols.

Partners
------
All synchrotons interested in analysing data using cloud resources & jupyter notebook.

Generalisation of Use Case
------
The pilot may be extended deploying Oneprovider and a PaNOSC Space for each RI.

Resources
------
EGI Notebooks service for supporting big data analytics
EGI DataHub/Onedata for federating data sets from the PaNOSC RIs
UmbrellaID as community AAI proxy for the PaNOSC community

Other resources
------
[Data transfer pilot on Github](https://github.com/EGI-Foundation/data-transfer-pilot)
[PaNOSC D6.1 Data-Hub](https://www.panosc.eu/wp-content/uploads/2020/12/D6.1_DataHub.pdf)
[PaNOSC data transfer pilot setup](https://documents.egi.eu/public/ShowDocument?docid=3686)
[EGI DataHub](https://docs.egi.eu/users/datahub/)
[EGI Notebooks service](https://www.egi.eu/services/notebooks/)

PaNOSC related work packages:
------
[WP6 – EOSC integration](https://www.panosc.eu/work-packages/work-package-6-eosc-integration/)

Contact person:
------
[Marco De Simone](mailto:marco.desimone@ceric-eric.eu) (CERIC-ERIC)

Link to website: 
------
https://www.panosc.eu/use-cases/use-case-7-data-transfer-using-egi-datahub-onedata/

------
Use Case 8 – Remote, collaborative access to beamline optics simulations (CERIC)
=========================================================

X-ray optics simulations are regularly performed both in the design of the beamlines and during experiments for alignment and/or experimental results validation. These simulations are usually performed by dedicated optics groups within synchrotrons and the beamline scientists are usually not the ones performing whole simulations, but only collaborate on the results. This process proves to be time consuming and cumbersome. The process can be simplified significantly if the simulation tool is placed into the cloud and a collaborative access is enabled. The software (in this case Oasys) can be accessed through any web browser and the files (Oasys workspaces) accessible to a given user are determined from their user permissions in the user portal (VUO – Virtual unified office). This way the scientist and the users can always access the updated version of the beamline Oasys workspace without installing the software. By the use of RAFEC remote application framework, all the remote computing resources are always available and the scientist can collaborate with the users in a particular workspace in real-time.

Description of needs
------
*Development of RAFEC – remote application framework;
*Adaption of Oasys for RAFEC;
*Setting up of machines providing cloud resources to the application.

Use case action flow
------
*Creation and upload of workspace: The workspace is created by the optics expert either locally or remotely in traditional way. If it was prepared locally, then the file is uploaded to the cloud.
*Remote access to the workspace: Users (beamline scientist or scientific users) login into the user portal (VUO) and spawn the remote application.
*Collaborative and updated work: Through the web browser all the users with permission can work in the same instance and collaborate on the same file.

Impacts from the implementation
------
Non-expert users can easily access X-ray optics simulations for a specific beamline. Before, these simulations were hard to access and only consulted by advanced users (due to long response time, as multiple people have to be involved).

Generalisation of Use Case
------
The use case can be generalised to any synchrotron beamline and through the use of other software as a remote application also to other pipelines.

Resources
------
OASYS, RAFEC

More on PaNOSC Github
------
[OASYS – WISER](https://github.com/oasys-elettra-kit/OASYS1-Wiser)
[OASYS Kit](https://github.com/oasys-kit/OASYS1)
[RAFEC](https://rafec.elettra.eu/)

Contact person
------
[Alessandra Gianoncelli](mailto:alessandra.gianoncelli@elettra.eu) (Elettra)

Link to website: 
------
https://www.panosc.eu/use-cases/use-case-8-remote-collaborative-access-to-beamline-optics-simulations/

------
Use Case 9 – Serial Femtosecond Crystallography Experiment Simulation (European XFEL)
=========================================================

Serial femtosecond crystallography is a powerful tool to resolve the structure of mesoscopic crystals, especially for small proteins. However, there are many complications, such as the pixel noise, unfunctional detector tiles and X-ray fluctuation, affecting the success of the experiment. By simulation with SimEx, one can predict the possible effects of the complications to help improve and validate the data analysis workflow.

Description of needs
------
The SimEx API in ViNYL package supported by PaNOSC.

Use case action flow
------
*Set up initial X-ray, detector and sample parameters.
*Run the diffraction simulation using the crystfel module integrated in SimEx.
*Change different detector geometries, noise response, respectively.
*Rerun the diffraction simulation.
*Set data analysis workflow using crystfel.
*Check the index results from different detector parameters to assess the complication effect.

Impacts from the implementation
------
It provides a tool for the users to validate their data analysis methodologies.

Generalisation of the use case
------
It can also be implemented for other SFX experiments.

Resources
------
[Example jupyter notebook repository](https://github.com/JunCEEE/crystalProject/tree/master/src/controller/panoscDEMO)
[SimEX on PaNOSC repository](https://github.com/PaNOSC-ViNYL/SimEx)

PaNOSC related work packages:
------
[WP5 – Virtual Neutron and X-ray Laboratory (VINYL)](https://www.panosc.eu/work-packages/work-package-5-virtual-neutron-and-x-ray-laboratory-vinyl/)

Contact person
------
[Juncheng E](mailto:juncheng.e@xfel.eu) (European XFEL)

Link to website:
------
https://www.panosc.eu/use-cases/use-case-9-serial-femtosecond-crystallography-experiment-simulation/

------
Use Case 10 – Linking raw data to the Protein Data Bank in Europe (PDBe) (ESRF)
=========================================================
The protein data bank ([PDBe in Europe](https://www.ebi.ac.uk/pdbe/)) is the reference repository for protein structures. All protein structures determined by different techniques are stored in the PDB. Since 2019 it is possible to link the protein structure entry to the raw data (images) often taken at the photon sources. As described in [this article](https://www.ebi.ac.uk/pdbe/about/news/links-added-raw-experimental-data-pdbe), “the model file in the PDB is the culmination of much hard work and interpretation of raw experimental data. The OneDep deposition system enables depositors to provide the location of raw datasets as a ‘digital object identifier’ (doi), within their mmCIF file in the PDB archive and this DOI is now directly linked from an entry page at PDBe”.

This use case is to link raw data in the ESRF data repository to the PDBe entries as shown in the [example here](https://www.ebi.ac.uk/pdbe/entry/pdb/6gv0).

Description of needs
------
Modify PaNOSC data repositories to add support for linking PDBe entries to raw data.

Use case action flow
------
*ESRF data repository – add javascript adapter for PDBe
*PDBe repository – test adapter
*Scientists – add DOI to raw data to PDBe entry

Impacts from the implementation
------
Make Protein Data Bank entries FAIR by providing access to raw data. This will enable results to be verified and structures to be refined with new software. This ICUR CommDat committee has been a strong advocate of making raw data accessible for crystallography [1]

[1] https://doi.org/10.1107/S2052252519005918

Generalisation of the use case
------
All PaNOSC and ExPaNDS partners could add the adapter for linking PDB entries to raw data. Thereby making PDB entries FAIRer.

Resources
------
ESRF data repository + PDBe adapter
[pDB 6gv0 structure summary](https://www.ebi.ac.uk/pdbe/entry/pdb/6gv0)

PaNOSC related work packages:
------
[WP3 – Data Catalogue Services](https://www.panosc.eu/work-packages/work-package-3-data-catalog-services/)

Contact person
------
[Andy Götz](mailto:andy.gotz@esrf.fr) (ESRF)

Link to website:
------
https://www.panosc.eu/use-cases/panosc-use-case-10-linking-raw-data-to-the-protein-data-bank-in-europe-pdbe/

------
Use case 11 – Create DOIs for datasets in paleontology database (ESRF)
=========================================================

The ESRF hosted paleontology database http://paleo.esrf.fr/ contains hundreds of unique datasets of ancient specimens from around the world. The database has been in existence since 2011. It contains mostly reconstructed data of 3D volumes of specimens. The specimens are mostly from museums around the world. Their ages range from thousands to hundreds of millions of years, which makes them difficult to access in real. Making the reconstructed 3D volumes available to scientists and the public in general is a very useful and relevant service for Open Science. Some of the data have been used in a number of publications, whereas other data are still to be exploited. The data are made freely available under a CC-BY-NC-SA license.

The use case is to create DOIs for each of the hundreds of datasets so that they can be cited in publications and be re-used by as many scientists as possible. Providing DOIs will make them more Findable, Accessible, Interoperable and Reusable, i.e. FAIR.

Description of needs
------
*DOIs for all datasets published on the https://doi.esrf.fr site;
*All datasets to be ingested into the ESRF data repository so they can be browsed and downloaded from the repository;
*The original url via http://paleo.esrf.eu must resolve to the data repository so that existing publications are still valid;
*A web portal which can be organised by categories to make it easy for users to browse (similar to paleo.esrf.eu).

Use case action flow
------
*Ingest paleo.esrf.eu datasets into ESRF icat data repository;
*Mint DOIs for each dataset;
*Archive datasets for 10 years or more.

Impacts from the implementation
------
Technical impact is that scientists can cite the paleontology data in their publications. Scientific impact is that it will encourage more scientists to re-use this data even if they were not part of the original experiment.

Generalisation of the use case
------
There is a general need to have DOIs on all data. This is not the case for old data or processed data. This use case highlights this need.

Resources
------
http://paleo.esrf.eu
https://gitlab.esrf.fr/icat/E-DataPortal
https://datacite.org/
https://data.esrf.fr
https://doi.esrf.fr

Other resources
------
Examples of datasets:
http://paleo.esrf.eu/picture.php?/5248/category/2846
http://paleo.esrf.eu/picture.php?/395/category/1539

PaNOSC related work packages:
------
[WP3 – Data Catalogue Services](https://www.panosc.eu/work-packages/work-package-3-data-catalog-services/)

Contact person
------
[Andy Götz](mailto:andy.gotz@esrf.fr) (ESRF)

Link to website:
------
https://www.panosc.eu/use-cases/panosc-use-case-11-create-dois-for-datasets-in-paleontology-database/
