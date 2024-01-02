*01/02/2024: A work in progress*

# FFT the Arctic 

![https://xkcd.com/26/](https://imgs.xkcd.com/comics/fourier.jpg)

This repo contains codes and data demonstrating how to perform spectral analyses on gridded topographic data at scale for the purposes of analyzing Arctic topography from various sources. 
1) I show how to load in and read lidar-derived topographic data for an area of interest (AOI)
2) I show how to query, download, and crop ArcticDEM from the Polar Geospatial Center for the same AOI
3) I show how Earth Engine can be used to query topographic (and multispectral!) data for the same AOI
4) I modify [Ben Purinton's Python version](https://github.com/bpurinton/DEM-FFT) of Taylor Perron's 2D spectral analysis to perform a 2D fast Fourier transform on all of the above data. 
5) A notebook that needs to be severely cleaned up shows you how to visualize all these power spectra (sorted in useful ways like by mean annual temperature and relief) using dictionaries and `plt.imshow()`. 

*01/02/2024*: Right now I'm cleaning it up but I'm uploading the code to do the inter-dataset comparison as well as upload the `.pkl` of the data and the plotting scripts I used for my 2023 AGU poster. My goal is for this month to have this repo in a more plug-and-play format. But for now, enjoy the spaghetti code. 