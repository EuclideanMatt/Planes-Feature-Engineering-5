# Feature Engineering for Flight Data: Layover Assignment & Additional Information

## Project Description
This project focuses on the assignment of layover values within a dataset of flight routes and the incorporation of additional key features. The primary goal is to enhance the dataset by feature engineering, specifically by calculating and assigning layover times using a newly created variable, `total_air_time`, as well as identifying specific flight characteristics such as red-eye flights, business class options, baggage information, and airport changes. The project leverages Python libraries such as `pandas`, `numpy`, `matplotlib`, and `seaborn` for data manipulation, analysis, and visualization.

## Layover Assignment
Layovers are assigned by calculating the difference between the total air time of consecutive flight segments. The idea is to determine how much time a flight spends at each stop before continuing to the next leg of the journey. The newly created `total_air_time` variable serves as the foundation for these calculations. By analyzing this data, the project assigns a specific layover duration to each stop along the flight route, providing valuable insights into travel patterns and potential delays.

## Additional Features
The project also focuses on engineering several other key features:
- **Red-Eye Flights**: Identifying flights that operate overnight and arrive early in the morning.
- **Business Class Availability**: Determining the availability of business class seating on certain flights.
- **Baggage Information**: Analyzing flights with and without check-in baggage options.
- **Airport Changes**: Capturing instances where a flight requires passengers to change airports during their journey.
- **No Information Available**: Handling cases where there is a lack of data for certain flight characteristics.


# Key Features & Code Explanation

* Data Importation and Initialization: The project begins by importing necessary Python libraries and loading the flight data.
* Feature Engineering: The core of the project focuses on creating the total_air_time variable and assigning layover values based on this metric. Additionally, key features such as red-eye flights, business class availability, baggage information, and airport changes are engineered.
* Data Visualization: Utilizes matplotlib and seaborn to visualize the results, including the distribution of layover times and other engineered features.
* Database Integration: The use of sqlite3 for database operations, allowing for efficient data handling and storage.

# Dataset Description
The dataset used in this project includes flight routes with several variables such as start, stop, and destination locations, as well as additional flight characteristics. The feature engineering process involves calculating layover times, identifying red-eye flights, and analyzing baggage and class options.










