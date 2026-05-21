## Chapter 9: Advanced Text Processing Tools

1. awk - Khud hi mai ek programming hai, is a standard, powerful text-processing and data extraction utility in Linux, designed for pattern scanning and processing of structured text files or data streams.
   ex. awk 'hmara code' {filename}

2. sed - (stream editor) is a powerful, non-interactive text processing tool in Linux that performs basic text transformations on an input stream (file or pipeline) by making a single pass through the data.  It is primarily used for **searching, filtering, and replacing text**, as well as inserting or deleting lines, making it ideal for automating repetitive editing tasks in shell scripts and configuration files.

3. grep - Global Regular Expression Print is a command-line utility in Linux and Unix systems used to search for specific patterns, words, or phrases within text files.  It scans files line by line and prints the lines that match the given pattern, making it essential for filtering logs, code, and data.

-> awk requires formatted data column by column, where as sed doesn't have such requirements and works line by line.

-> awk and sed differs in syntax