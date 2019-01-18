<p><img src="https://github.com/profLewis/Geog2021_Coursework/blob/master/images/ucl_logo.png?raw=true" align="left" \>
    
<img src="https://www.nceo.ac.uk/wp-content/themes/nceo/assets/images/logos/img_logo_purple.svg" align="right" /></p>



[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/profLewis/Wooster_fire_practical/master?filepath=docs%2FFireEmissionsPractical.ipynb)



Introduction
============

The purpose of this exercise is to provide you with some 
practical experience of the sort of products that are obtained on
vegetation fires and biomass burning from Earth orbiting satellites,
and an overview of how these fit into the IPCC Greenhouse Gas (GHG)
Inventory Process. 


Learning outcomes
=================

-   Understand the basis of the IPPCC process for estimating GHG
    emission from vegetation fires, and be able to use the basic
    spreadsheets involved in this calculation.

-   Understand the basics of Active Fire and Burned Area datasets and
    how they are derived from remote sensing observations, appreciating
    their main advantages and disadvantages

-   Visualise active fire datasets and burned area datasets, and apply some
    simple processing to these (modifying supplied Python scripts)

### Running on your own computer

If you want run this on your own computer, you can do that easily. Follow these steps:

1. First, download or clone the entire repository. 
    a. You can download everything as a zip file, and uncompress it,
    b. ... Or you can do `git clone https://github.com/jgomezdans/geog0133-practicals` if you have git installed
2. Make sure you have Anaconda Python installed, and in the folder with the practicals issue the following command:

    ```
    conda env create -f environment.yml
    ```
3. The previous command can take a while to run, and needs the internet to download stuff.
4. You can then (hopefully) just run `jupyter notebook` on that folder
