# Backend-takehome-problem

# Purpose of the Code:

This program scrapes article information from PubMed using a list of PubMed IDs and saves the extracted data into a CSV file.

# Key Libraries Used:

requests – to fetch web page content.

BeautifulSoup from bs4 – to parse and extract HTML content.

json – to format data for console output.

csv – to write the results into a CSV file.

re (Regular Expressions) – to find email addresses.

#Main Steps Performed:

1. Fetch HTML page for each PubMed ID.
   
2. Extract:
   
    Title
   
    Publication Date
   
    Author Names
   
    Email of Corresponding Authors

3. Format data into dictionary for each paper.

4. Print the extracted data in JSON format.

5. Save all data into a CSV file (pubmed_papers.csv).
