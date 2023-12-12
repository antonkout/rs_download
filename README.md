# Satellite Data Download Scripts

This repository contains scripts for downloading satellite data from various sources, including Sentinel-1, Sentinel-2, Sentinel-5P, and Landsat.

## Table of Contents
- [Introduction](#introduction)
- [Supported Satellite Missions](#supported-satellite-missions)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Downloading satellite data for remote sensing applications can be a crucial step in various projects. This repository provides scripts that facilitate the download of data from different satellite missions. Whether you're working with synthetic aperture radar (SAR) data from Sentinel-1, multispectral data from Sentinel-2, atmospheric composition data from Sentinel-5P, or optical imagery from Landsat, these scripts aim to streamline the data retrieval process.

## Supported Satellite Missions

- **Sentinel-1:** Synthetic Aperture Radar (SAR) data for earth observation.
- **Sentinel-2:** Multispectral imagery for land monitoring.
- **Sentinel-5P:** Atmospheric composition monitoring, including pollutants and greenhouse gases.
- **Landsat:** High-resolution optical imagery for land cover analysis.

## Repository Structure

The repository is organized as follows:

- `credentials.json`: File containing credentials for accessing satellite data services.
- `elegant-tide-219210-592108e3651a.json`: Another file related to credentials setup.
- `environment.yml`: Environment configuration file, specifying dependencies.
- `landsat.ipynb`: Jupyter Notebook for Landsat data download and analysis.
- `poetry.lock`: Poetry lock file for Python dependency management.
- `pyproject.toml`: Poetry project file for managing project dependencies.
- `sentinel1.ipynb`: Jupyter Notebook for Sentinel-1 data download and analysis.
- `sentinel2.ipynb`: Jupyter Notebook for Sentinel-2 data download and analysis.
- `sentinel5p.ipynb`: Jupyter Notebook for Sentinel-5P data download and analysis.

## Getting Started

To use the scripts in this repository, follow these steps:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```
Explore the folders corresponding to each satellite mission and find the relevant Jupyter Notebooks for data download and analysis.

## Usage
Each Jupyter Notebook provides a guide for downloading and analyzing data. Ensure you have the necessary credentials and dependencies configured before running the notebooks.

## Contributing
Contributions are welcome! If you have ideas for improvements, feature requests, or bug reports, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License.
