# 🚴 Fremont Bridge Bicycle Count Time Series Analysis

This project explores time series data of bicycle counts collected from automated sensors installed on Seattle’s Fremont Bridge. The goal is to analyze and visualize bicycle traffic patterns over time using various data aggregation and smoothing techniques.

---

## 📌 Objective

To analyze hourly bicycle count data and uncover meaningful trends and patterns in bicycle traffic on the Fremont Bridge. This includes examining seasonal variation, daily usage patterns, and overall traffic behavior.

---

## 🗂️ Dataset Description

- The dataset contains hourly bicycle counts recorded by inductive sensors on the east and west sidewalks of the Fremont Bridge.
- Data collection started in late 2012.
- Each record corresponds to the total number of bicycles passing the sensors during a given hour.
- The dataset includes separate counts for the east and west sidewalks, which are combined to provide a total count.

---

## 🔍 Data Analysis and Insights

### Data Preparation

The dataset is indexed by date and time, allowing for easy time series manipulation. Columns are renamed for clarity, and a total bicycle count column is added.

### Summary Statistics

Basic descriptive statistics provide insight into the distribution and variability of bicycle counts.

### Visualizing Raw Data

Plotting the raw hourly counts reveals the overall scale and variability in bicycle traffic but is dense and difficult to interpret due to the large number of data points.

### Resampling for Clarity

By resampling the data to a weekly frequency and summing counts, seasonal trends become apparent. This highlights increased bicycle use during summer months and lower counts during winter.

### Rolling Mean Smoothing

Applying rolling mean techniques smooths the data to reveal underlying trends more clearly. A 30-day rolling average provides a general sense of changes over time, while Gaussian window smoothing offers an even smoother trend line.

### Time-of-Day Patterns

Grouping the data by the time of day exposes daily traffic patterns. This analysis shows how bicycle usage varies across different hours, illustrating peak and off-peak times.

---

## 🧰 Tools and Libraries Used

- Pandas for data manipulation and time series handling.
- Matplotlib and Seaborn for data visualization.
- NumPy for numerical operations.

---

## 🎯 Conclusion

This project demonstrates effective methods for analyzing large-scale time series data, including resampling, smoothing, and grouping. The bicycle count data reveals strong seasonal cycles, daily usage patterns, and overall trends that can inform city planning and traffic management.

---

## 📚 References

- Data Source: Seattle Fremont Bridge Bicycle Counter (City of Seattle Open Data)
- Time Series Analysis Techniques: Pandas Documentation, Data Science Tutorials

---
