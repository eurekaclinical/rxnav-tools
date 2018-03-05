# RxNav Tools
Georgia Clinical and Translational Science Alliance, Emory University, Atlanta, GA

## What does it do?
This project contains bash shell scripts for using the National Institutes of Health's RxNav web services. They should run in any recent Linux environment.

## Version history
Nothing released yet.

## Tools
### NDC to RxNorm mapper
Uses RxNav to map NDC codes to their RxNorm equivalents.

#### Usage:
`ndc-to-rxnorm [<input_file> [<output_file>]]`

The command accepts two file arguments. The first should contain NDC codes, 1 per line. The second is tab-delimited file with two columns. The first is an NDC code, and the second is a comma-separated list of the corresponding RxNorm codes. If output_file is omitted, the command writes to stdout. If input_file and output_file are missing, the command reads from stdin and writes to stdout.
