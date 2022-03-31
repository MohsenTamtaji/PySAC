# PySAC
A python based Machine Lreaning (ML) algorithm for the gibbs free enegy of various intermediates on single atom catalysts (SACs)
************************************************************
Developed by Mohsen Tamtaji (mtamtaji@connect.ust.hk) Under supervision of Professor Tom Luo at HKUST

ML algorithm for the prediction of Gibbss free energy of N2*, H*, OH*, O*, OOH*, COOH*, CO*, and CHO* intermediates for NRR, HER, ORR, and CO2RR

SVR model is trained based on 2104 data in the literature for graphene-based SACs

The ML model is applicable for all the 3d, 4d, and 5d transition metals (TM) embedded into nitrogen-doped graphen-based SACs with the structures of TM@N4, TM@N3C1, TM@N2C2, TM@N1C3, TM@C4, TM@C3, and TM@C2. It distinguished the effect of pyrrolic and pyridinic nitrogen in SAC structre.

************************************************************

*Requirments:

1-rdkit (https://www.rdkit.org/docs/Install.html)

2-mendleev(https://pypi.org/project/mendeleev/)

3- matplotlib

4- numpy

************************************************************

*Run the program:

Note: there is not "pip install" of this version yet, so you need to download the ML algorithm and run the program as follows:

1- Download the PySAC2.sav and Propertyoriginal.pkl files into your directory

2- Put the .mol file of your graphen-based SAC into your directory (you need to prepare .mol file of SAC structure by using Avogadro or other softwares. You may chack the Test.mol file)

3- Download the PySAC.py and put into your directory, open in your PyCharm, Spider, or other Python environments, change the directory (Location) and filename in the PySAC.py file and run the code. The program will generate 3 figure for HER, ORR, and CO2RR and also will give you the overpotential and limiting potential of ORR. The free energy of N2*, H*, OH*, O*, OOH*, COOH*, CO*, and CHO* intermediates will be wrote into a .txt file which will be saved is in your directory.

4- Enjoy :)

************************************************************

*Citation:

For the citation, please cite the following papers:

1- DOI: 10.1039/D1TA08337F 

2- https://doi.org/10.1021/acsanm.1c01436
