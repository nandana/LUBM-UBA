# LUBM-UBA
[Lehigh University Benchmark (LUBM) - Data Generator(UBA)](http://swat.cse.lehigh.edu/projects/lubm/)

A copy of the LUBM data generator. 

This tool generates syntetic OWL or DAML+OIL data over the Univ-Bench ontology in the unit of a university. These data are repeatable and customizable, by allowing user to specify seed for random number generation, the number of universities, and the starting index of the universities

## Usage

> java -jar uba-1.7-SNAPSHOT.jar 
> 
> Usage: Generator
>        [-univ <num of universities(1~2147483647)>]
>        [-index <start index(0~2147483647)>]
>        [-seed <seed(0~2147483647)>]
>        [-daml]
>        -onto <univ-bench ontology url>
>
> An Example:
> java -jar uba-1.7-SNAPSHOT.jar -univ 8000 -onto http://swat.cse.lehigh.edu/onto/univ-bench.owl 
