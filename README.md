# WordInsight
__WordInsight__ is a text analysis tool that extracts, tokenizes, and analyzes data from XML files to identify patterns in word usage. 

## Overview
It ranks the top 10 most frequent words and leverages word distance algorithms to find the most similar words based on semantic and structural characteristics. This project is useful for linguistic analysis, NLP tasks, and exploring relationships between words.

## Features
- Extract and process text from XML files.
- Tokenize text using spaCy for accurate linguistic processing.
- Compute word frequencies and save them as word_count.csv.
- Identify the top 10 most frequent words.
- Calculate word distances using various algorithms:
    - __Jaro Distance__
    - __Jaro-Winkler Distance__
    - __Longest Common Subsequence (LCS) Distance__
    - __Longest Common Substring Distance__

## Installation

1. Clone this repository:
```
git clone https://github.com/yourusername/WordInsight.git
cd WordInsight
```

2. Create a virtual environment and activate it:
```
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

3. Install dependencies:
```
pip install -r requirements.txt
```

## Usage
1. Open the Jupyter Notebook notebook.ipynb to follow the data extraction, tokenization, and analysis steps.

2. Run each cell in the notebook to process data, generate word_count.csv, and calculate word distances.

## Word Distance Algorithms
The following algorithms are used to compute the similarity between words:
- __Jaro Distance:__ Measures the edit distance between two strings.
- __Jaro-Winkler Distance:__ A modified version of Jaro that gives more weight to matching prefixes.
- __Longest Common Subsequence (LCS):__ Measures the longest sequence of characters present in the same order in both strings.
- __Longest Common Substring:__ Calculates the longest substring shared between two strings.

For additional algorithms, explore the 16_word_distance_algorithms/ folder.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any changes.
