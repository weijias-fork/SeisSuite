The following is a list of things to-do to improve the SeisSuite package.

1. Attempt to keep the CHANGES.txt file up-to-date
2. Allow for choice of where the config is stored in case the os.getcwd() option is not desirable. 
3. Allow for choice of different extensions in create_database.py
4. Get the new_station_search.py script to work with config file!
5. Integrate option to either have the linear stack or the phase-weighted stack used for FTAN
6. Add if __name__ == '__main__' support for all tools that don't already have it. 
7. Improve the initialisation of the SQL databases from 01_database_init.py to run as functions and not run during importation. 
8. Create functional tool to search frequency response window in the response.db, and also create tests to check if the response.db is correct!
9. Create new timeline database to keep track of when the processing for preprocessing and xcorr is. This is in case the whole terminal crashes or is interupted for any reason. Currently it uses pickle, but SQL feels like a better fit for the task. 
10. Fix problems with False multiprocess option in 02_timeseries_process.py
11. 