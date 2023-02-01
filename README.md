# Project1: command-line tool in data engineering with Rust
This project leverages the Apache Arrow ecosystem and the Apache Arrow DataFusion framework to build a simple data processing command-line tool. This framework is based on the Arrow format and enables quick and easy data transformation of CSV or Parquet files.

## Objectives
* Read and process end-user command-line arguments
* Read a Parquet or CSV file using the [Apache Arrow DataFusion crate](https://arrow.apache.org/datafusion/)
* Apply a simple transformation to a dataset
* Write the results as a Parquet or CSV file

## Progress Week1: CLI Tool with Clap
* Define the project directories and the dependencies.
* Define the program structure and describe the main code blocks.
* Parsing the command-line arguments using the Clap crate.

## Progress Week2: Load, Transform & Write with Apache Arrow DataFusion
* Define some utilities and struct to manage errors.
* Load, Transform and Write data.

## References

* [rust-cli-template](https://github.com/kbknapp/rust-cli-template)
* [Data Engineering With Rust And Apache Arrow DataFusion](https://medium.com/@MatthieuL49/data-processing-with-rust-and-apache-arrow-datafusion-introduction-d036cc96a3f4)
