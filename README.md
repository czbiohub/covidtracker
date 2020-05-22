# COVID Tracker CA

A build of [nextstrain](nextstrain.org) focused on California, using public GISAID sequences. Contains:

* All CA sequences
* Sequences from the rest of the world which are closest to CA by BLAST
* Context from rest of world selected using standard subsampling

The final tree is then pruned to just CA sequences, their direct ancestors, and contextual sequences with genomes identical to the direct ancestors. This is meant to enhance visibility, and to focus on introductions to and dynamics within CA.
