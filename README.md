# bima_planner
These codes were created to prepare an observation plan for the Eclipsing Binaries Minima (BIMA) 2.0 Monitoring Project (Budi et al 2024 J. Phys.: Conf. Ser. 2866 012075, DOI 10.1088/1742-6596/2866/1/012075). 

The codes will compute next time of primary minima during any given observing time and create plot of simplified light curve (assumed as sinusoidal; the secondary minima are at phase 0.5 or shown as maxima on the graphs). 

- bima_ephem_1.ipynb: calculate ephemerides from Krakow eclipsing binary catalog (https://www.as.up.krakow.pl/ephem).
- bima_ephem_2.ipynb: calculate ephemerides from user's input (single object).
- bima_ephem_3.ipynb: calculate ephemerides from user's input (multiple object in a csv table).

If you are using Krakow eclipsing binary catalog, please refer to J.M. Kreiner, 2004, Acta Astronomica, vol. 54, pp 207-210.

Notes: If the code return a warning: "Only one minimum found for {obj}, cannot plot light curve" then you must input a longer time of observation.

Result example: 

<img src="https://github.com/user-attachments/assets/13956f9b-589c-43bf-a28f-df1809b88b7b" width="600"/>
