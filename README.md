# google_map_restaurant_scraping
Google Map Scraping Practice Project. This tool allows you to add restaurant types to a dropdown list, search for restaurant details based on the selected type, and save the results in a JSON file.

## Overview
This Project is a technical practice exercise designed to demonstrate web scaping techniques using Google Maps. The primary goal is to explore and learn how to extract data from Google Maps for educational purposes.
This project is not intended to encourage or promote the use of web scraping to obtain data from Google without proper authorization.

## Disclaimer
**This project is for educational purposes only.** The scraping techniques demonstrated in this project should not be used in production environments or for any commercial purposes.
Users should be aware that scraping data from Google Maps without permission may violate Google's Terms of Service and could result in legal consequences

## Features
- Automated data extraction from Google Maps using Selenium.
- Collects data such as restaurant names, addresses, and other details.

## Adding Restaurant Types to the Dropdown Widget
If you want to add restaurant types (EX.Fried Chicken) to the dropdown widget for selection, you can refer to the example code below:
```python
dropdown = widgets.Dropdown(
    options=[
        "Hotpot", 
        "Fried Chicken", 
        "Sushi",
        # Add more types as needed
    ],
    value="Hotpot",  # Default selection
    description="Choose:",
    disabled=False,
)
```
## demo :
![git](https://github.com/user-attachments/assets/e6568800-a9a5-4dac-a207-f04748c514aa)

   
