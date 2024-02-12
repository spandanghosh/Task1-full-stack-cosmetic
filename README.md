# Automated Content Creation with Semantic Scholar and PubMed Integration

This Python script automates content creation by incorporating data from Semantic Scholar and PubMed, offering a convenient way to enhance content with scholarly information. The output is stored in a CSV file for easy accessibility and analysis.

## Overview

The script performs the following key tasks:

1. **Data Retrieval:**
   - Utilizes the Semantic Scholar API to fetch relevant data for a given research paper title.
   - Utilizes the PubMed API to retrieve PubMed IDs (PMIDs) associated with the provided title.

2. **Content Creation:**
   - The `create_content` function acts as a placeholder for custom content creation logic. It currently prints the title and fetched data.

3. **CSV Storage:**
   - The `store_in_csv` function writes the title, Semantic Scholar data, and PubMed data to a CSV file named "output.csv."

4. **Google Colab Compatibility:**
   - Modified to run seamlessly on Google Colab, including the installation of the `beautifulsoup4` library and the ability to download the CSV file.

## Usage

1. Replace the example title ("Your Research Paper Title") with the actual title you want to query.
2. Customize the `create_content` function to align with specific content creation requirements.
3. Execute the script, and the output will be stored in the "output.csv" file.

## Dependencies

Ensure the following libraries are installed before running the script:

```bash
pip install beautifulsoup4
