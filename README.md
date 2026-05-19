# ADBQuery
Accessing the ESA's Gaia Observatory database to derive stellar distances via parallax.

This project directly builds off the PIMA Source Document (24 March 2024) from the Spring 2024 independant study by adding astroquery to your project environment.  The document is included in this repository.  

First, open the appropriate terminal for your OS (for Windows open an Anaconda Powershell terminal), move to your project directory, and activate your pima environment.  

For Windows:  
&ensp;> cd pima    
&ensp;> conda activate pima  

For Linux:  
&ensp;$ cd pima  
&ensp;$ conda activate pima

For MacOS:  
&ensp;% cd pima   
&ensp;% conda activate pima  

Once that is resolved, enter one of the following:
&ensp;python -m pip install -U --pre astroquery[all]

or:
&ensp;conda install -c conda-forge astroquery

You can now open jupyter notebook and access the ADQuery notebook page.

Astronomy Database Query © 2026 by David Vance is licensed under CC BY 4.0. To view a copy of this license, visit https://creativecommons.org/licenses/by/4.0/

