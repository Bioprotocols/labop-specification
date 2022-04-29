# PAML Specification

PAML is the Protocol Activity Markup Language

## LaTeX build instructions:

All of the material necessary to build the LaTeX document should be in this repository. 
The master file is `paml.tex`

## UML build instructions:

If the underlying PAML model has changed, and you need to rebuild the diagrams, you can build the UML using the following instructions.

Run this in first the OPIL, then the PAML directory to build the UML:

```
cd OPIL
pip3 install -e .
cd ../PAML
python3 -m opil -i paml/paml.ttl -n http://bioprotocols.org/paml# -d ../PAML-specification/uml -v
```
