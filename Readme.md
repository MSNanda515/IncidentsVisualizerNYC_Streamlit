# Incident Visualizer

This is a data analytics based web application. It allows you to explore and interact with data. 

It uses the publically available Motor Vehicle Crash data from the New York City as its primary dataset.

## Questions Asked
* Where are the most people injured in NYC?
* How many collisions occur during a given time of day?

It also provides further visualizations based on the minutes past the specified hour and the kind of accident.

## Technology Stack
The application is built using the following technologies:
* Python as the primary programming language
* Streamlit for the widgets in the web app
* pandas and numpy to analyze and process the data
* pydeck for the 3d map interface
* plotly express for the interactive histogram

## Running instructions:
Install the python packages and then start the server using the following commands.
```sh
pip3 install -r requirements.txt
streamlit run app.py
```

The app opens on port 8501 by default. You can change this by passing another cli argument.


A demo of the application can be found at the following link:

[Incident Visualizer](https://incident-visualizer-streamlit.herokuapp.com/)

