This program utilizes the Beautiful Soup package to scrape data about U.S states
and territories population. The data is then cleaned up and put into a pandas
dataframe. Finally, the data is uploaded to a csv file called us_info.csv

To execute the program, from the command line convert the code from notebook to
python by using this command:
jupyter nbconvert --to python nb.ipynb

After the command has been ran, execute the program like a python program by doing:
python nb.py

You may need to install the python mistune package for this to work and here is the
command for that:
sudo pip install -U mistune
