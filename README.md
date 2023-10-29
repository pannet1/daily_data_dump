# Daily Data Dump

This project is a allows you to download daily data from NorenRestApi

## Overview

We look for symbols and respective exchange in the `input` folder in a desired location. All files mentioned are processed one after the other. The output files are generated in the `output` directory.

## Setup

1. Clone the repository: `git clone <repository_url>`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Configure the settings in the `daily_data_dump.yaml` file and place it in the desired location.

## Configuration

The `daily_data_dump.yml` file contains date of dump required alongwith the credentials of NorenRestApi account.

## Results

After running the script, the program will generate a feather file with the date mentioned in the settings file as prefix.
