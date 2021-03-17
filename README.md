# PAML Specification

PAML is the Protocol Activity Markup Language

## UML build instructions:

Run this in first the OPIL, then the PAML directory to build the UML:

cd OPIL
pip3 install -e .
cd ../PAML
python3 -m opil -i paml/paml.ttl -n http://bioprotocols.org/paml# -d ../PAML-specification/uml -v
