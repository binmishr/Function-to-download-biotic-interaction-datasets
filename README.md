# Function-to-download-biotic-interaction-datasets

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

A Brief Introduction
=====================

I work in ecology, biogeography, etc… Biotic interactions (interactions between species) and its repercussions on species distributions is my main research interest.

As such, I had, at some point, to download datasets on species interactions. I wanted to be able to produce a uniform (more or less, not as much as I would like) R object whatever the database I used. I created this function to do just that!

It can be used to download from database website or upload csv files into R (depending on the database). It currently uses the following databases:

    1.EcoBase – The database for the models using Ecopath with Ecosim. These are really good, have good metadata and spatial information (polygons) (Christensen & Walters, 2004; Heymans       et al. 2016).
    2.Web of Life – To be really honest I don’t know this database all that much. However it also provides information on the dataset location, but it does not provide details on the 
    ecosystem where it occurs (Fortuna et al. 2014).
    3.Global Web – This database provides details on the ecosystem where the interaction dataset occur, bu no details on spatial location are provided (Thompson et al. 2012).
    4.Mangal – This database provides lots of information on the biotic interactions datasets (Poisot et al. 2015).

EcoBase DataSet: http://sirs.agrocampus-ouest.fr/EcoBase/
