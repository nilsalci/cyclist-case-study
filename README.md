# A Case Study on Bike usage by subscribed and non-subscribed members

## Project Description
This project analyzes data from the Pedalist bike-sharing system to uncover differences in usage patterns between casual riders and annual members. The insights derived from this analysis will inform marketing strategies aimed at converting casual riders into annual members. The dataset spans from September 2020 to August 2021 and includes ride details such as start/end times, station locations, and user types.

## Data Sources
- **Pedalist Trip Data (Sept 2020 - Aug 2021)**: Contains details of individual bike trips, including ride IDs, bike types, user categories, and start/end times and locations etc.
- **Pedalist Data Repository**: ([Data Source]https://divvy-tripdata.s3.amazonaws.com/index.html)

## Technologies and Tools
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Visualization Tools**: Bar and line charts for trend analysis

## Analysis Steps

### Data Cleaning:
- Removed invalid entries and null values.
- Standardized station names and converted timestamps into usable formats.

### Feature Engineering:
- Calculated ride duration and distance.
- Extracted additional time-based features (e.g., hour, day of week, season).

### Exploratory Data Analysis (EDA):
- Visualized ride patterns by user type, bike type, and time.
- Analyzed popular stations and routes.

### User Segmentation:
- Compared casual riders and members based on ride duration, frequency, and station preferences.

## Key Findings
- **Casual Riders vs. Members**:
  - Casual users use bikes more on weekends, while member users use bikes more on weekdays.
  - Casual users ride longer, member users prefer shorter.
  - Casual users prefer touristic, central areas.
  - Peak riding hours are morning and evening on weekends.

- **Popular Stations and Routes**:
  - High-traffic stations include Clark St & Wrightwood Ave and Canal St & Adams St.
  - Casual riders often choose scenic or leisure routes, while members focus on commutes.

- **Temporal Trends**:
  - Casual riders peak in summer months, particularly in July and August.
  - Members maintain steady usage year-round, with slight drops in winter.

## Recommendations
- **Promotions for Casual Riders**:
  - Offer discounts on annual memberships during peak casual rider seasons.
  - Highlight membership benefits such as unlimited rides or reduced costs for frequent users.

- **Targeted Campaigns**:
  - Deploy campaigns at high-traffic stations during weekends and summer months.
  - Use data-driven insights to design personalized offers based on casual rider behavior.

- **Enhanced User Experience**:
  - Improve station facilities at scenic or popular locations.
  - Introduce bike-sharing guides or ride recommendations for casual users.

## How to Run the Project

### Prerequisites
- Python 3.7+
- Required Libraries: Pandas, NumPy, Matplotlib, Seaborn

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/nilsalci/cyclist-case-study
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook CyclistCaseStudy.ipynb
   ```

## Contributors

- [@Sevag9](https://github.com/Sevag9)
- [@nilsalci](https://github.com/nilsalci)

## References

- [Bike Sharing Dataset](https://divvy-tripdata.s3.amazonaws.com/index.html)
  
---
