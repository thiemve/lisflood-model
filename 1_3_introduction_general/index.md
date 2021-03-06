## Further notes about the model

The LISFLOOD model is a hydrological rainfall-runoff model that can help simulate the main hydrological processes that occur in a catchment area. 


LISFLOOD has been developed by the Joint Research Centre (JRC) of the European Commission, building on earlier models such as LISEM, HBV and WOFOST. The specific development objective was to produce a tool that can be used in large and transnational catchments for a variety of applications, including:


*	Flood simulation and forecasting;
*	Water resource simulation in river basins;
*	Assessing the effects of land-use changes;
*	Assessing the effects of measures such as river regulation measures and water efficiency measures;
*	Assessing the effects of climate change.


Although there are a wide variety of hydrological models that are suitable for each of these individual tasks, few single models are capable of doing all these jobs. Besides, our objective requires a model that is spatially distributed and, at least to a certain extent, physically based. Also, the focus of our work is on European catchments. Since several databases exist that contain pan-European information on soils (King et al., 1997; Wösten et al., 1999), land cover (CEC, 1993), topography (Hiederer & de Roo, 2003) and meteorology (Rijks et al., 1998), it would be advantageous to have a model that makes the best possible use of these data. Finally, the wide scope of our objective implies that changes and extensions to the model will be required from time to time. Therefore, it is essential to have a model code that can be easily maintained and modified.


LISFLOOD has been specifically developed to satisfy these requirements. The model is designed to be applied across a wide range of spatial and temporal scales. 


LISFLOOD is grid-based, and applications so far have employed grid cells of as little as 100 metres (for medium-sized catchments), to 5,000 metres for modelling the whole of Europe and up to 0.1° (around 10 km) for modelling on a global scale. 


Long-term water balance can be simulated (using a daily time step), as can individual flood events (using hourly time intervals, or even smaller). The output of a "water balance run" can be used to provide the initial conditions of a "flood run". 

Although the model's primary output product is channel discharge, all internal rate and state variables (soil moisture, for example) can also be written as output. In addition, all output can be written as grids, or time series at user-defined points or areas. The user has complete control over how output is written, thus minimising any waste of disk space or CPU time.
