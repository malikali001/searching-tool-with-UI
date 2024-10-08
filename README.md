# Facility Search Tool

This project is a simple, interactive facility search tool built using Python, JSON data, and `ipywidgets`. It allows users to search for facilities from a JSON file, select a facility from a dropdown list, and confirm the selection to retrieve the facility's ID.

## Features

- **Search Functionality**: Users can enter search text to look for facilities in the provided dataset.
- **Dropdown Selection**: Matching facilities are displayed in a dropdown for easy selection.
- **Facility ID Retrieval**: Once a facility is selected, its unique ID is displayed.

## How It Works

1. The facilities' data is loaded from a `facilities.json` file, which contains a list of facilities with their names and corresponding IDs.
2. A search box allows users to enter the name (or part of the name) of a facility.
3. The results matching the search term are displayed in a dropdown for selection.
4. Once a facility is selected, the user can confirm their choice, and the facility's ID is displayed in the output area.

## Requirements

- Python 3.x
- Jupyter Notebook
- `ipywidgets` library

