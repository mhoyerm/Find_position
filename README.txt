Find Position

Analyzes the net charge in stretches of 30 amino acids in the viral proteome, comparing with a chosen cut-off charge and for each protein it returns the absolute and relative position of the stretch which net charge is higher than the chosen charge.

Usage:
find_position.py <input fasta file> <output file name> <charge>
input (required): Input complete file name as for example "example.fasta"
output (required): Output complete file name, it generates "output_example.txt"
charge (required): Cut-off charge
  
Output example:


Protein stretches of 30
Containing charges higher than 2

protein;charge;absolute position;relative position
sp|Q0SXE3|DSBD_SHIF8;2;43;0.0761061946903
sp|P98032|COX2_DAUMA;2;158;0.696035242291
sp|O03848|COX2_LATCH;2;158;0.683982683983
sp|Q9XDB2|DSBD_TATCI;3;40;0.0692041522491
