
# Recalculating IMD

This repository contains the code and analysis for recalculating the Index of Multiple Deprivation (IMD) with a specific focus on including or excluding the crime indicator when using it to explain crime. The project was developed to accompany a blog post for the British Society of Criminology.

## Overview

The IMD is a vital tool in understanding deprivation and its relationship with various societal factors, including crime. However it includes crime as one of its indicators. Is this a problem when using it for such analysis? We show that most likely this does not impact much on the types of conclusions researchers and analysts will draw. 

## Repository Structure

- `Cleaned_IMD_recalculation_writeup.Rmd`: Main R Markdown document containing the analysis, code, and narrative.
- `data/`: Directory containing datasets used in the analysis. (Note: Due to size or confidentiality constraints, some datasets might not be included. Please refer to the Rmd file for data sourcing details.)
- `figures/`: Directory containing generated plots and visualizations.

## Usage

To replicate the analysis, ensure you have R installed along with the necessary packages mentioned in the Rmd file. Clone the repository and run the Rmd file in your preferred R environment.

## Data Source

The data used in this analysis is sourced from [UK Police Data](https://data.police.uk/).

## Contributing

If you find any inconsistencies or have suggestions, please open an issue or submit a pull request.

## Acknowledgements
A special thanks to Stephen Clark (University of Leeds) who introduced and advised Lightowlers on this as a possible approach to pursuing the analysis in Lightowlers et al. (2021) and Dr Jose Pina-Sánchez (University of Leeds) for comments on an earlier draft of this blog. and the British Society of Criminology for providing a platform to share this work. 

## License

This project is open-source and available under the [MIT License](LICENSE).

