#HTML to Markdown Batch Converter

This script automates the conversion of multiple HTML files into a single, clean Markdown document. It is specifically optimized for creating clean datasets for LLMs or personal knowledge bases.
Features

    Batch Processing: Converts all .html files in the directory.

    Format Preservation: Maintains tables and links while stripping unnecessary images.

    Single Output: Merges all converted content into OUTPUT_FİLE.md with clear source headings.

Requirements

    Python 3.x

    html2text library

Install dependencies:
    Bash
pip install html2text

Usage

    Place the script in the folder containing your .html files.

    Run the script: python html_to_md.py
