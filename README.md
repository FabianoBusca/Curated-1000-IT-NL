# Curated-1000-IT-NL Dataset

## Overview

The **Curated-1000-IT-NL** dataset was created to support machine translation tasks and linguistic research between Italian and Dutch. This dataset focuses on five specific linguistic phenomena:

1. Subject Omission
2. Reflexive Constructions
3. Double Negation
4. Diminutives and Augmentatives
5. Clitic Pronouns

It consists of 1,000 sentence pairs selected from the Tatoeba Project and additional sentences generated using large language models to fill gaps for underrepresented phenomena. All generated data was manually reviewed to ensure quality.

## Dataset Citation

If you use this dataset, please cite it as follows:

Derived from the Tatoeba Project, available at [https://tatoeba.org](https://tatoeba.org). For details on licensing, see [Tatoeba Terms of Use](https://tatoeba.org/en/terms_of_use).

## Project Structure

The repository is organized as follows:

```
├── curator.ipynb                      # Jupyter notebook for the dataset curation process
├── analyst.ipynb                      # Jupyter notebook for dataset analysis
├── Dataset/
│   ├── Curated-1000-IT-NL.tsv         # Final curated dataset
│   ├── Tatoeba-it-nl.tsv              # Original Tatoeba dataset for Italian-Dutch
│   ├── Diminutives-Augmentatives-Generated-IT-NL.tsv # Generated data for diminutives/augmentatives
│   ├── Double-Negation-Generated-IT-NL.tsv          # Generated data for double negation
```

## Installation

To run the `analyst.ipynb` notebook, you will need the [SentITA library](https://github.com/NicGian/SentITA).

## Usage

1. Use the `curator.ipynb` notebook to understand and reproduce the curation process.
2. Use the `analyst.ipynb` notebook to analyze the dataset. Ensure you have `sentITA` installed.
3. The dataset is available in the `Dataset` folder in TSV format, which can be directly loaded into your projects.

## Limitations

The dataset is heavily focused on five linguistic phenomena (60%) and may not provide sufficient coverage for other linguistic aspects. Additionally, it does not include disordered speech or significant regional language variations.

## License

This dataset is distributed under a [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/). Please ensure proper attribution when using it in your work.

## Contributing

Contributions are welcome! If you would like to enhance the dataset or fix errors, feel free to submit a pull request. Report issues via the GitHub issue tracker.

## Acknowledgments

This dataset is derived from the Tatoeba Project ([https://tatoeba.org](https://tatoeba.org)), licensed under CC BY 2.0 FR. Additional sentences were generated using tools like DeepL and ChatGPT and reviewed manually.

## Contact

For questions or issues, please open an issue in this repository.
