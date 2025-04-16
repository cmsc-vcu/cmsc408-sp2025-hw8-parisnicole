# Homework 8 - World Bank Analysis

This project is a data analysis assignment for CMSC 408, exploring World Bank data using SQL and Python. The analysis is conducted through a Quarto report, which connects to the CMSC VCU database and performs a variety of data queries to answer specific questions.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributor](#contributor)

## Introduction

The goal of this assignment is to query and analyze a World Bank dataset hosted on a the CMSC VCU server. Tasks include retrieving records, performing aggregations, and answering questions using SQL embedded in a Quarto document.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/cmsc-vcu/cmsc408-sp2025-hw8-parisnicole
   cd cmsc408-sp2025-hw8-parisnicole
   ```

2. Install the required packages

3. Install Quarto (if not already installed)

## Usage

To run the report and generate the output:

```bash
quarto render report.qmd
```
Ensure that the database is accessible and your environment variables are correctly configured before rendering.

## Features

Connects to a SQL database (CMSC VCU) using helper utilities

Executes SQL queries and renders results as HTML tables in report

Structured analysis with clearly defined tasks and outputs


## Dependencies

Make sure the following Python packages are installed

* pandas
* jupyter
* quarto

## Configuration
```bash
CMSC408_HW8_USER=sp25_eid
CMSC408_HW8_PASSWORD=Shout4_eid_joY
CMSC408_HW8_HOST=cmsc-vcu.com
CMSC408_HW8_DB_NAME=sp25_eid_user
```
You can create a .env file in the root directory and populate it with the above variables.


## Troubleshooting
Quarto not found: Make sure Quarto is installed and accessible in your system's PATH.

Database connection error: Verify .env credentials and confirm the database server is running.

Python import errors: Ensure you've installed all packages


## Contributor
Paris Davis