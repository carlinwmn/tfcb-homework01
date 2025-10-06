# Homework #1: Git, GitHub, Markdown, and file organization

This repository contains source code, data, and images from an original `messy-project-directory`. Below are descriptions of the contents of the resulting tidied file folders.

## Code

This folder contains source code files for FormicID, a computational tool to identify ant species.

| Filename | Function |
| :------- | :------: |
| main | This file initializes the model and trains the model, after which training is evaluated and the model is tested. |
| get_dataset     | Functions for downloading and handling the datasets.   |
| get_species_list   | Script to create a .csv file with the species that are imaged the most. Images are pulled from [AntWeb](https://www.gbif.org/dataset/13b70480-bd69-11dd-b15f-b8a03c50a862).  |
| predict_image   | Load a model with trained weights and predict an image or a test set.   |


## Data

Survey data including observations on:

* Species
* Sex
* Plot observed
* Weight (g)
* Date recorded


## Images

Example images of ants:

* _Rhytidoponera metallica_
  
![](./images/casent0172345_Rhytidoponera_metallica.jpg)

* _Camponotus darwinii_

  ![](./images/casent0191696_Camponotus_darwinii.jpg)
  
* _Anthomyrmex ferox_
  
  ![](./images/casent0901788_p_1_high_Acanthomyrmex_ferox.jpg)
  
* _Cataglyphis fortis_
  
  ![](./images/casent0906296_p_1_high_Cataglyphis_fortis.jpg)
  
  
