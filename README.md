# Geospatial Explorer (for local machine)
## Description
- Built an interactive user interface using React and Leaflet that allows the user to enter their monthly budget and
**amenity proximity preferences** across Mumbai
- The backend was made using Flask which receives 6 relevant parameters to delineate the preferred housing regions
- The user can see the highlighted regions that fit their personal selections and can finalise the region they want to live based on their opinion
- Further information is provided in the report

## Dependencies 
1. QGIS: The QGIS library is necessary for working with spatial data and performing geospatial operations. Make sure you have QGIS installed on your system.
2. Python Dependencies including pip3, PyQt5, Flask, etc.
3. Flask: Flask is a Python web framework used for building web applications. It is required to run the Flask server in this project.
4. npm: For running the React frontend

## How to Run Code
### Backend:
Go to the `backend` folder and run `/Applications/QGIS.app/Contents/MacOS/bin/python3 server.py`

### Frontend: 
Go to the `mumbai-housing-project` folder and run `npm i`. After that, run `npm start`.
