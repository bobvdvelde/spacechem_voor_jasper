# SolutionNet (spacechem.net)

This A COPY OF  the source code for [SolutionNet](http://spacechem.net), a site for sharing and comparing solutions for the game [SpaceChem](http://www.spacechemthegame.com).

## Disclaimers/Warnings

The goal is only to help out someone looking to get some development on this project going. 

## Getting a dev instance running

It appears the original project did not use virtualenvironments. To get started: 

You should build this distribution by 

?) Starting a virtualenvironment (optional but strongly recommended)
1) Running pip install -I -r /path/to/Requirments.txt (gets the required modules)
2) copy spacechem.cfg.example > spacechem.cfg AND add appropriate values (especially for the database)
3) copy spacechem.wsgi.example > spacechem.wsgi AND change the path to reflect the location of your spacechem folder
4) Run spacechem.py by using python (on windows, you might want to do this using IDLE or IPython to see bug reports) 

That's it for now folks! 

! CURRENT VERSION NOT SUCCESFULLY TESTED ON WINDOWS ! 