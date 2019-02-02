# Explorations of the Baseball Stats Database
The notebooks in this repo step you through how to use and document the `lahman2016.sqlite` database. 
- Part 1 is a light primer on SQLite.
- Part 2 is an ERD-drawing exercise (so we can visualize the database).  

__These exercises are intended to complement the class lectures. DO NOT START THEM EARLY.__

Just in case ... This is a huge database to hold in memory. Don't for example, select everything from the Batting table. If Jupyter become unresponsive when you open Part1.ipynb, then 
1. Shut down all kernels
2. Use the Git menu to Open a Terminal
3. Type 
```bash
python remove_output.py Part1.ipynb
```
4. You should get a new file that you can edit and run from scratch. Delete the old notebook and replace (rename) it with the new one. 