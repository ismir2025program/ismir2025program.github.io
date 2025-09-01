# Welcome to ISMIR 2025 virtual platform creation code!!
Run with Python 3.8

1. Clone this repo 
2. Clone complete metadata from: https://github.com/ismir2025program/miniconf-data
3. Post the above steps you should have the two repos `ismir2025program.github.io` and `miniconf-data` under the same folder
4. Go to `ismir2025program.github.io` folder and run `>> python miniconf_prep.py` this will prepare the data as required by miniconf. Read through this code for the details of preprocessing
5. To build the miniconf site and run it locally try: `>> export FLASK_DEBUG=True; export FLASK_DEVELOPMENT=True; python main.py --path sitedata/`
6. To build the site in production push the committed changes to the `main` branch of remote.