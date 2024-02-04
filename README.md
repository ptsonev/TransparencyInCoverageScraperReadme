# Transparency In Coverage Scraper

## Installing Python
1) Download and install Python<br/>
	32-bit Windows:<br/>
	https://www.python.org/ftp/python/3.11.0/python-3.11.0.exe<br/>
	
	64-bit Windows:<br/>
	https://www.python.org/ftp/python/3.11.0/python-3.11.0-amd64.exe<br/>
	
	**Make sure to check the "Add python.exe to PATH" at the bottom of the installation window.**<br/>
	![image](https://drive.google.com/uc?export=view&id=1CqbfL0qezreCyh4GvQTOmwwILhPlwWnO)

## Installing the requirements
Open a command prompt and navigate to the scraper's directory.<br/> 
The easiest way is to open the scraper's folder and type cmd in the address bar.
![image](https://drive.google.com/uc?export=view&id=10WuqSabT4Ylti7koCkuDeahneW7eCdmo)
<br/>
Type the following command, you have to do this only once:<br/>
```
pip install -r requirements.txt
```

## Starting the scraper
Each insurance company(Cigna, UnitedHealthcare, Anthem and Aetna) will have a separate script.<br/>
You can start the script for UnitedHealthcare by typing the following command:<br/>
```
python uhc.py
```
For Windows, you can also start it by using 'py' instead of 'python':
```
py uhc.py
```

## Stoping the scraper
You can stop the scraper prematurely by pressing CTRL+C <br/>
It will track which files have been parsed, so if you restart it, the scraper will skip the already completed files. <br/>

## Output
Each script will save a CSV file with the following name:<br/>
CompanyName_year-month-day_out-of-network.csv <br/>
```
UnitedHealthcare_2024-02-01_out-of-network.csv
```

