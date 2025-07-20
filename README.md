# 🎧 Spotify Dashboard | Power BI Project

An immersive, interactive Power BI dashboard that explores Spotify’s most-streamed tracks of 2023.
Crafted with a custom-designed Figma background, this project blends real-world music data, audio feature analysis, and sleek visual storytelling — delivering a dynamic, Spotify-themed analytics experience built on an external dataset.

<img src="./Snapshot of Dashboard _ Default.png">

---

## 📌 Features

- 🎨 **Custom background** — Designed in Figma with a Spotify theme and glassmorphism.
- 📅 **Date slicer** — Select tracks by year, month, or release date range.
- 🎛️ **Reset button** — One-click reset to clear all filters and return to default view.
- 📈 **Interactive visuals** — 
  - Bar chart for top streamed tracks  
  - Line chart for release trends  
  - KPIs that change with filters (e.g., top streams, averages, etc.)
- 🎧 **Audio features displayed** — Danceability, Acousticness, Valence, etc.
- 📦 **Auto calendar table** — Created using Bravo for Power BI.

---

## 🛠 Tools Used

| Tool            | Purpose                                               |
|-----------------|-------------------------------------------------------|
| Power BI        | Dashboard development and data visualization         |
| Power Query     | Data cleaning, transformation, and shaping           |
| DAX             | Calculated columns, KPIs, and dynamic visuals        |
| Figma           | Designing Spotify-style glassmorphism background     |
| Excel           | Initial dataset formatting and minor adjustments     |
| Bravo for Power BI | Auto-generating calendar table                    |

---

## 🚀 How It Works

1. **Data Import**  
   - The dataset (`.xlsx`) containing top-streamed Spotify tracks is loaded into Power BI.
   - Power Query is used to clean and format data (e.g., convert release date, handle missing URLs).

2. **Calendar Table**  
   - A dynamic date table is created using **Bravo for Power BI** to support time-based filtering.

3. **Data Modeling & Measures**  
   - Relationships are set between tables.
   - DAX is used to calculate metrics like:
     - Total Streams  
     - Average Streams  
     - Count of Tracks  
     - First release date of selected track

4. **Dashboard Design**  
   - Layout styled using a **Figma-designed Spotify-themed background**.
   - Glassmorphism aesthetic with vibrant visuals and clean white cards.

5. **Interactivity**  
   - Slicers for artist, track name, and release date allow deep filtering.
   - A **reset button** is added to clear all filters and return to the default view.
   - All visuals are connected — selections in one chart reflect across others.

6. **Album Covers**  
   - Track-level album art is pulled using the provided `cover_url` (some missing).

---

## 📷 Preview

### 🔹 Default view  
![Default](Snapshot%20of%20Dashboard%20_%20Default.png)

### 🔹 Artist filter: Drake  
![Drake](Snapshot%20of%20Dashboard%20_%20Drake.png)

### 🔹 Selected tracks view  
![Selected Tracks](Snapshot%20of%20Dashboard%20_%20Selected%20Tracks.png)

---

## 📁 File Structure
```
📁 Spotify Dashboard Repository
├── README.md
├── SpotifyDashboard.pbit
├── Spotify Most Streamed Songs 2023 Dataset - Spotify Most Streamed Songs 2023 Dataset - October 2023.xlsx
├── Spotify Dashboard Background.png
├── Snapshot of Dashboard _ Default.png
├── Snapshot of Dashboard _ Drake.png
├── Snapshot of Dashboard _ Selected Tracks.png
```

---

## 🗃 Dataset Overview

- Top-streamed songs (2015–2023)
- Fields include:
  - Track & artist name  
  - Stream counts  
  - Release date  
  - Audio features (danceability, valence, etc.)  
  - Album cover image (some missing)

---

## 📈 Use Cases

- 🎵 **Music Trend Analysis**  
  Identify which artists or tracks dominated Spotify streams across years.

- 📊 **Data Visualization Portfolio**  
  Showcase your Power BI and design skills using a real-world dataset.

- 🧪 **Audio Feature Exploration**  
  Compare how danceability, energy, or valence differ across top songs.

- 📅 **Time-Based Insights**  
  Filter songs by release date and observe popularity trends over time.

- 🧑‍🏫 **Educational Tool**  
  A great example to understand how to integrate visuals, DAX, and Power Query in Power BI.

- 📁 **Template for Similar Projects**  
  Can be reused or extended for other music platforms or streaming datasets.

---

## 🛠️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/Anushka-Sharma-008/SpotifyDashboard.git
   ```
2. Open the .pbit file in Power BI Desktop.
3. When prompted, load the .xlsx dataset (Spotify Top Tracks) included in the repository.
4. Let Power BI connect and transform the data using Power Query.
5. Explore the dashboard:
6. Use slicers to filter by artist, track, or release date.
7. Click the reset button to clear all filters and return to default view.
- ⚠️ Note: Album covers may not load for all tracks due to missing or invalid cover_url entries.

---

## 📌 Notes

- Some tracks are missing album art (`cover_url = Not Found`).
- To refresh the visuals completely, click the reset button in the top-right corner.

---

## 🙋‍♀️ Author

**Anushka Sharma**  
🌐 [LinkedIn](https://www.linkedin.com/in/anushkasharma008/) • 🐱 [GitHub](https://github.com/Anushka-Sharma-008) 
🎓 Learning Data Science, Analytics & Machine Learning

---

## ⭐ Show Your Support

If you found this project helpful or inspiring:

- ⭐ Star this repository  
- 🛠️ Fork it to build upon or adapt it for your own use
- 💬 Share feedback or suggestions via Issues/Discussions
