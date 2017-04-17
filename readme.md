Wrangling OpenStreetMap data

This project involves the gathering and extraction of xml data from open street maps for the city of Los Angeles and shape it to a structured format to enable data-driven applications. Data scientists generally spend 80% of their time acquiring and cleaning data to get it ready for analysis. More details about the open street map project can be found at https://www.openstreetmap.org.

After the wrangling phase, I use SQL to analyze the data to figure out how users contribute to the maps data and suggest methods to improve the data quality.

This project has been completed with the use of python as I'm a big fan of the functionality of its regular expressions.

To run the ipython notebook file, download this repository as a zip file or execute this link from the terminal -> git clone https://github.com/shawar8/Making-sense-of-OpenStreetMap-Data.git

Navigate to the directory where you unzipped the files and host a local server using -> python -m SimpleHTTPServer 8888. 

Execute Ipython notebook from the terminal shell. 

Open the titanic.ipynb file. 

Libraries used:
		
			cerberus
			sqlite3
			xml.etree
			re
			schema
			codecs

To install cerberus -> https://pypi.python.org/pypi/Cerberus

Have fun!