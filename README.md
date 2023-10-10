# bigdata_603
# Assignment 2: MapReduce Assignment

## Introduction

In this assignment, you will use MapReduce to analyze data from the Harry Potter book series. The data is sourced from the Harry Potter Books and provided in a PDF format. The main tasks involve extracting specific pages from the books and performing word analysis using Python code and MapReduce.

### Attached Files

- [Harry_Potter_(www.ztcprep.com).pdf](link-to-the-pdf-file)

## Data Acquisition

For this assignment, follow these steps to acquire the necessary data:

1. **Download Harry Potter Data**: Download the Harry Potter Books data from the following link (PDF is also attached): [Harry Potter Data Download](https://ztcprep.com/library/story/Harry_Potter/Harry_Potter_(www.ztcprep.com).pdf)

## Data Extraction

Follow these steps to extract the required data:

1. **Select Book by Birth Month**: Choose the Harry Potter book that corresponds to your birth month. For birth months 8-12, divide the month number by 2 and round up to determine the book.

2. **Select Pages by Birth Date**: Go to the page number that corresponds to your birth date (1-31) and extract the next 10 pages of the book to a text file named `file1.txt`.

3. **Select Pages by Birth Year**: Go to the page number that corresponds to your birth year (last 2 digits). If your birth year is in 2000 or later, add '1' in front of the year number to find the page number (e.g., year 2000 becomes 100, 2001 becomes 101, and so on). Extract the next 10 pages into another text file named `file2.txt`.

## Data Analysis

### Task 1: Word Frequency Analysis

Write Python code to perform the following analysis on `file1.txt`:

- Use MapReduce to count the occurrences of each word.
- Determine how many times each word is repeated.

### Task 2: Non-English Word Analysis

Write Python code to perform the following analysis on `file2.txt`:

- Use MapReduce to count how many times non-English words (e.g., names, places, spells) are used.
- List those non-English words and the number of times each word was repeated.

You can use various libraries such as [pyenchant](https://pypi.org/project/pyenchant/), [pyspellchecker](https://pyspellchecker.readthedocs.io/en/latest/), or manually download a list of words from [this source](http://www.gwicks.net/dictionaries.htm) to identify non-English words.

## Submission

Please submit your assignment with the following components:

1. Python code for both Task 1 and Task 2.
2. The extracted `file1.txt` and `file2.txt` containing the data you analyzed.
3. Any additional files or documentation required for your analysis.

Good luck with your assignment!
