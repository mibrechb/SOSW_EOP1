# <img src="https://drive.google.com/uc?id=1hNy2r6O4RlkPv_jzw48FVxpW-HRYGsWX" width="80"> SOS-Water - EOP1 SPM Mapper

The Earth Observation Prototype 1 (EOP1) for Suspended Particulate Matter (SPM) retrieval is a prototype algorithm designed to estimate suspended sediment concentrations in lakes and rivers using Sentinel-2 MSI and Landsat-7/8/9 ETM+/OLI/OLI-2 data. This prototype addresses data gaps related to sediment flows, particularly in the Mekong basin, which are critical for maintaining ecosystem health and delta stability. The model offers high-resolution (30 to 10 meters) mapping capabilities and supports both monitoring applications and historical analysis dating back to April 1999. 

This repository is part of the Deliverable 3.2 of SOS-Water - Water Resources System Safe Operating Space in a Changing Climate and Society ([DOI:10.3030/101059264](https://cordis.europa.eu/project/id/101059264)). 

Check out the project website at [sos-water.eu](https://sos-water.eu) for more information on the project.

## How to use

To use the provided code and notebooks it is necessary to setup a Google Earth Engine account ([GEE account registration](https://code.earthengine.google.com/register)) and have an python environment with the needed dependencies.

### Setup python environment (conda)
- Build a conda environment from the provided YAML file in `setup/environment.yaml`:<br/>
`conda create --name sosw_eop1 --file setup/environment.yaml`

## Technical Notes

Detailed technical notes on the algorithm used are available [here]().

## Disclaimer
Views and opinions expressed are those of the author(s) only and do not necessarily reflect those of the European Union or CINEA. Neither the European Union nor the granting authority can be held responsible for them.

## Acknowledgement of funding
<table style="border: none;">
  <tr>
    <td><img src="https://github.com/user-attachments/assets/515e254d-9216-4e37-945c-7bdf59a907bf" alt="EU Logo" width="150"/></td>
    <td>This project has received funding from the European Union’s Horizon Europe research and innovation programme under grant agreement No 101059264.</td>
  </tr>
</table>
