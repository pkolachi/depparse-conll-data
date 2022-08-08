code-udpipe.conllu ... predicted segmentation and morphology, no syntax
code.txt ............. raw text input

The system must read metadata.json to obtain the list of test sets it is
supposed to process. Each test set has a record in the list, and the fields in
the record are interpreted as follows:

* lcode ..... language code (for UD languages same as in UD; but other
              languages may appear here too)
* tcode ..... treebank code (for UD treebanks same as in UD; but extra non-UD
              treebanks may appear here too)
* rawfile ... name of raw text file (input of systems that do their own
              segmentation)
* psegmorfile ... name of CoNLL-U file with segmentation and morphology
              predicted by a baseline system (currently UDPipe)
* outfile ... name of the corresponding CoNLL-U file that the system must
              generate in the output folder

Extra fields not needed by the participating system:

* goldfile ... name of the corresponding gold-standard file to be used by the
               evaluation script (in a separate folder)
