# Extract-Tabular-data-From-Any-PDF
It is a Python Guide to Extracting Tabular Data from pdf with pdfplumber

In the realm of data science, one recurring challenge involves extracting valuable information, especially tabular data, from PDF documents. Over time, I've experimented with various packages tailored for this task, but one has truly stood out as a personal favorite: pdfplumber.

Let me share with you a comprehensive guide, encapsulated in a Jupyter notebook, outlining step-by-step instructions for leveraging pdfplumber to extract tabular data seamlessly. 
Let's dive in and unlock the potential of pdfplumber together!

Other package you can explore 
1. fitz  # PyMuPDF
2. tabula



__Github link of pdfplumber__: https://github.com/jsvine/pdfplumber


__Table of content in Jupyter notebook:__
1. Importing the library pdfplumber
2. Load the pdf and display
3. extract simple table
4. extract more complext table(two parallel table in a single page)
5. Debugging the page by Croping the page Using custom .extract_table's settings
6. Save all extracted data into a dataframe
