# Springfield vs. Shelbyville: Music Preferences Analysis

![Status](https://img.shields.io/badge/Status-In%20Progress-brightgreen)  
![Python](https://img.shields.io/badge/Python-3.11%2B-blue)  
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)   

---

## Project Description

This project explores **music preferences between Springfield and Shelbyville** using Python-based data analysis techniques.  
The main goal is to **identify patterns and differences in listening behavior** — genres, artists, and activity time — across both cities.

The project involves:
- Exploratory Data Analysis (EDA) of music streaming data.  
- Comparative visualization of user behavior by city.  
- Comparative visualization of user behavior by days.  

---

## Dataset

**File(s):**
- `data/raw/music_preferences.csv`

**Main Columns:**
- `user_id` → unique user identifier.  
- `city` → either Springfield or Shelbyville.  
- `genre`, `artist`, `track` → metadata for each song.  
- `timestamp` → listening time.  
- `duration_ms` → track duration.  

---

## Methodology

1. **Data Preparation**
   - Load dataset with `pandas`.  
   - Handle missing values and inconsistent genres.  
   - Convert timestamps to `datetime` objects.  

2. **Exploratory Data Analysis (EDA)**
   - Analyze listening counts by city, genre, and time of day.  
   - Identify top artists per region.  
   - Visualize patterns using `matplotlib`.  

3. **Visualization**
   - Bar charts for comparative analysis.  

4. **Insights & Reporting**
   - Highlight most popular genres per city.  
   - Draw conclusions about cultural or behavioral factors.  

---

## Technologies Used

- **Language:** Python 3.11+  
- **Libraries:**  
  - `pandas` — data manipulation  
  - `numpy` — numerical operations  
  - `matplotlib` — data visualization  
  - `jupyter` — exploratory notebooks  

---

## Conclusion

This project demonstrates how data-driven analysis can uncover meaningful cultural and behavioral insights from music listening habits.
By comparing Springfield and Shelbyville, we can identify that certain genres, artists, and listening times reflect distinct lifestyle patterns between the two cities.
The findings highlight the importance of localized data analytics in understanding audience segmentation, marketing strategy, and cultural diversity.

---

## Author  

**Gerzon Medina Ortiz**  
📧 [gerzon13medin@gmail.com](mailto:gerzon13medin@gmail.com)  
💼 [LinkedIn](https://www.linkedin.com/in/gerzon-medina-robotics-datascience)  