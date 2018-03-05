# NDC to RxNorm mapping tool
Georgia Clinical and Translational Science Alliance, Emory University, Atlanta, GA

## What does it do?
This is a bash shell script that uses the National Institutes of Health RxNav web service to map NDC codes to their RxNorm equivalent.

## Version history
Nothing released yet.

## Usage:
ndc-to-rxnorm [<input_file> [<output_file>]]

The command accepts two file arguments. The first should contain NDC codes, 1 per line. The second is the file to which the mappings will be written. If output_file is omitted, the command writes to stdout. If input_file and output_file are missing, the command reads from stdin and writes to stdout.