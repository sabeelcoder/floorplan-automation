# floorplan-automation

Refer to http://www.samuelaston.com/#/automated-plan/ for full project explanation. 

The Dynamo files interact with Revit software to extract and transform room and building data from the 3D model. The datasets are exported into CSV format which is in turn transformed, analyzed, predicted upon and updated in the Jupyter Notebook.

In the Jupyter Notebook, I extract and transform the data to allow for exploratory analysis, which is also documented in detail in this notebook. From there, I use a regression algorithm to make predictions on likely new floorplan schemes based on user input unit boundaries. New wall locations are then plotted and kicked back into Dynamo, where a new 3D model is generated. 
