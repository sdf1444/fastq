## Fastq

This project provides a command-line utility for working with FASTQ files. It includes functionality for determining the number of sequences and nucleotides in a FASTQ file, even if the file is compressed with gzip.

## Requirements
Python 3.7 or higher.
See requirements.txt for a list of required Python packages.

## Installation
1. Clone the repository to your local machine.
2. Create a virtual environment using virtualenv or conda.
3. Activate the virtual environment.
4. Install the required packages by running pip install -r requirements.txt.

## Usage
To use the command-line utility, run fastq_utils.py with path to the FASTQ file within src folder with desired options. The available options are:
  1. -s: Prints the number of sequences in the file.
  2. -n: Prints the number of nucleotides in the file.

For example, to count the sequences in a FASTQ file called test.fastq, run the following command:
  `python fastq_utils.py ../test_files/test.fastq -s` in src folder where the script is.

To count the nucleotides in a gzip-compressed FASTQ file called test.fastq.gz, run the following command:
  `python fastq_utils.py ../test_files/test.fastq.gz -n` in src folder where the script is.

## Contributing
If you would like to contribute to this project, please follow these steps:
  1. Fork the repository.
  2. Create a new branch for your changes.
  3. Make your changes and write tests to ensure that they work as expected.
  4. Submit a pull request with a clear description of your changes and the problem they solve.

## Continuous Integration
This project uses GitHub Actions for continuous integration (CI). Each time a pull request is created or a commit is made to the main branch, the tests will be automatically run to ensure that the changes haven't introduced any errors. If the tests fail, the pull request or commit will not be merged until the errors are resolved. This helps ensure that the project remains in a stable state, and makes it easier to collaborate with other developers.

## License
This project is licensed under the MIT License.