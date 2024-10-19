# NoSQL Demonstration Project and Data Modeling with MongoDB

This project demonstrates the use of MongoDB to manage data related to wildfire detection from MODIS Terra/Aqua satellite data. It simulates a scenario of an environmental research center that requires an efficient infrastructure to store and analyze data.

## Context

In this project, MongoDB is used to model and manage data from multiple sources, such as MODIS satellite data, country boundaries, government data, and event reports. The data structure may vary and evolve over time.

## System Requirements

To run this project, you will need:

- MongoDB
- Python 3
- Data to download at: "https://drive.google.com/drive/folders/1ustCKZTFa43lTiO8X_H_8PCr5zHWhzzv?usp=sharing"
- Python libraries: pymongo, pandas, numpy, pathlib, matplotlib, datetime, time, json, folium

## Project Setup

1. Clone this repository to your local machine.
2. Make sure MongoDB is running on your system.
3. Run the `clean_preprocess_fire.ipynb` notebook to preprocess the data.
4. Run the `Proyecto_NoSQL_IntiLuna.ipynb` notebook to perform data insertion, index creation, and queries.

## Data Structure

The data is modeled using documents in MongoDB, allowing for variable data and flexible schemas. The documents represent fire detection records and include information on coordinates, intensity, satellite, and other relevant fields.

## Contributions

Contributions are welcome! If you have suggestions for improvements, bug fixes, or want to add new features, feel free to submit a pull request.
