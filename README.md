# Video-Retention-Analysis->

## Objective  
To analyze how viewers engage with videos by measuring their retention at different time points (10s, 30s, 60s, 90s). The goal is to identify when viewers drop off and understand which videos keep people watching longer.

## Dataset  
- 5 sample videos with total views and viewer counts at various time stamps  
- Columns: video_id, title, views, retention at 10s, 30s, 60s, and 90s  

## Methodology  
1. **Data Cleaning:** Removed videos with fewer than 1000 views to ensure reliable analysis.  
2. **Calculations:**  
   - Converted raw retention numbers into percentages for easy comparison.  
   - Calculated viewer drop-off between intervals (10-30s, 30-60s, 60-90s).  
3. **Visualization:** Plotted retention curves for individual videos showing % viewers remaining over time.  
4. **Insights:**  
   - Measured average drop-off rates to identify critical points where viewers lose interest.

## Key Findings  
- Most viewers drop off between **10 seconds and 30 seconds**, highlighting the importance of strong hooks in the first half-minute.  
- Videos with engaging intros tend to have higher retention throughout the video.  
- Retention steadily decreases, but drop-off slows down after 60 seconds for well-performing videos.



## Conclusion  
Understanding video retention patterns helps creators optimize content to maintain viewer interest. This analysis can guide improvements in video length, structure, and early engagement strategies to maximize watch time.

## Tools Used  
- Python (Pandas, NumPy, Matplotlib) for data processing and visualization.

- # Screenshots
![Graph image](https://raw.githubusercontent.com/your-username/image-host/main/image.png)

