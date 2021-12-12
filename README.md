# Differential Reddening Correction

Dust and other matter in the intersellar medium along the line of sight scatters and absorbs the light coming from distant objects.
This results in these objects appearing dimmer and redder than they actually are, these effects are known as **extinction** and **interstellar reddening** respectively.

Differential reddening, or Spatially-variable extinction, occurs in all directions throughout the Galaxy and is also present across the field of view of most 
Open clusters (OCs). This non-systematic spatial deviation from the actual colour and magnitude of the member sources in different parts of the Open clusters
leads to the broadening of evolutionary sequences (like Main sequence) in the colour-magnitude diagram (CMD). This makes is difficult the precise determination of fundamental 
parameters, especially the age, metallicity and distance of OCs. The jupyter notebooks in this repository correct for this differential reddening in [ML-MOC](https://arxiv.org/abs/2011.13622) members of Berekeley 39 and NGC 6819. 
For each star in the field, we selected the nearest 30 sources as reference stars and calculate the median shift in BP-RP (colour) needed to move the reference stars to the main sequence. This is assumed as the reddening correction for the target star.
