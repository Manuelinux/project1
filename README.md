To run this demo in jenkins use:

PYTHONPATH=''
nosetests --with-xunit --all-modules --traverse-namespace --with-coverage --cover-package=project1 --cover-inclusive
python -m coverage xml --include=project1*
pylint -f parseable -d I0011,R0801 project1 | tee pylint.out

cleaning comments
Testing!
ya me canse!!
mas cansado
otra linea
borre una
ya la volvi a poner
