# Advanced NLP with Python for Machine Learning - Course Exercises

## Overview
This notebook contains exercises and solutions for building NLP processing pipelines using spaCy, covering topics like tokenization, POS tagging, dependency parsing, and named entity recognition.

## Exercises

### Exercise 1: Load Resources
**Objective**: Set up spaCy and load English language model resources.

**Key Steps**:
- Import spaCy and pandas
- Download and load the English model (`en_core_web_sm`)
- Understand spaCy's default processing pipeline order:
  1. Tokenization
  2. Stop Words Removal
  3. POS Tagging
  4. Dependency Parsing
  5. Lemmatization
  6. Named Entity Recognition
  7. Other Tasks

**Solution**: Demonstrates basic text processing including tokenization, NER, and POS tagging.

### Exercise 2: Build a Simple Processing Pipeline
**Objective**: Create a complete text processing pipeline.

**Pipeline Components**:
- Tokenization
- Stop Words Removal
- POS Tagging
- Dependency Parsing
- Lemmatization
- Named Entity Recognition

**Solution**: Processes sample text through each pipeline step with output examples.

### Exercise 3: Build a Processing Pipeline with a File
**Objective**: Process text from a file through the NLP pipeline.

**Key Features**:
- Reads text from `sentiment_examples.txt`
- Applies full processing pipeline
- Includes detailed output for each processing step

**Solution**: Shows complete pipeline execution on file content with tokenization, stop word removal, POS tagging, etc.

### Exercise 4 (Optional): Exploratory Data Analysis
**Objective**: Perform basic statistical analysis of processed text data.

**Analysis Includes**:
- Token counts
- Sentence counts
- Stop word frequencies
- Most frequent words and POS tags
- Named entity analysis
- Lexical diversity metrics

## Key spaCapabilities Demonstrated
- Text processing pipeline construction
- Linguistic feature extraction
- File-based processing
- Basic NLP statistics and analysis

## Usage
The notebook provides practical examples for:
1. Setting up spaCy environments
2. Building custom NLP pipelines
3. Processing text from various sources
4. Analyzing linguistic features

Each exercise includes complete code solutions with example outputs.
