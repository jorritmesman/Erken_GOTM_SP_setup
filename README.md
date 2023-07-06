# Erken_GOTM_SP_setup
Setup of the GOTM-Selmaprotbas model for Lake Erken

The files in this repository replicate the main model run in the publication "Drivers of phytoplankton responses to summer wind events in a stratified lake: A modeling study", by J.P. Mesman, A.I. Ayala, S. Goyette, J. Kasparian, R. Marcé, H. Markensten, J.A.A. Stelzer, M. Thayne, M.K. Thomas, D.C. Pierson, and B.W. Ibelings (2022), Limnology and Oceanography, 67(4), 856-873, doi:10.1002/lno.12040

- To run the model, clone this repository, open command prompt, navigate to the folder on your local machine in command prompt, and type `gotm`

- The executable provided works on Windows 10, but will not work on MacOS or Linux. In that case, you will have to compile GOTM-Selmaprotbas yourself; see code & instructions on https://github.com/jorritmesman/selmaprotbas. 

- To run the base (i.e. no wind perturbations) RCP8.5 simulation, you need to replace the references to the meteorological file inside gotm.yaml to `Erken_MetFile_1960-2020_climate_run.dat`. Note that in this file, air temperatures have only been scaled from 1991 onwards.  

- To run the other scenarios in the study, you need to follow the description in the Methodology section (or contact the corresponding author). 
