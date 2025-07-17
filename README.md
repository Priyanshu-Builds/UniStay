# 🏨 UniStay – Smart PG/Hostel Recommendation System

UniStay is a machine learning-based recommendation engine that helps students find the most suitable PGs or hostels based on location, preferences, and clustering analysis. It leverages geolocation data, clustering algorithms (K-Means and Self-Organizing Maps), and mapping APIs to enhance the discovery experience.

---
<img width="1625" height="691" alt="Screenshot 2025-07-16 212723" src="https://github.com/user-attachments/assets/9ee43757-da06-4c01-9a3d-e6accb768bd0" />


## 📌 Features

- 📍 **Location-Aware Matching**  
  Recommends nearby accommodations based on geospatial coordinates.

- 🤖 **Clustering with ML**  
  Groups accommodations using **K-Means** and **MiniSom (Self-Organizing Maps)** to uncover hidden patterns in preferences.

- 🧹 **Data Preprocessing Pipelines**  
  Handles numerical, categorical, and geospatial data from over 5,000 listings.

- 🗺️ **Map Visualization**  
  Maps 200+ PGs/hostels using interactive Map APIs to assist with exploration.

- ⚡ **Optimized Search & Relevance**  
  Ensures fast and relevant recommendations through query optimization and feature scaling.

---

## 🔐 API Key Required

This project uses a **Geolocation API (e.g., Foursquare, Google Maps, etc.)** for address-to-coordinate conversion or place search.

> **Important:** The API key is not included in this repository for security reasons.

### ➤ To run the notebook successfully:

1. **Get your own API key** from the provider (e.g., [Foursquare Developer Console](https://developer.foursquare.com/)).
2. In the notebook, locate the line that looks like:

   ```python
   API_KEY = "YOUR_API_KEY_HERE"

## 🛠️ Technologies Used

- **Languages/Libraries**: Python, NumPy, Pandas, Scikit-learn, MiniSom
- **Mapping & Geolocation**: Geopy, Geolocation API (Google Maps or similar)
- **Visualization**: Matplotlib, Seaborn, Folium (if used)

---

## 📁 Project Structure

```

UniStay/
│
├── UniStay.ipynb              # Jupyter Notebook containing full implementation
├── dataset.csv                # Cleaned dataset with PG/hostel listings (sample or full)
├── README.md                  # Project documentation

````

> You can adapt `dataset.csv` and add `.py` files if you wish to modularize the code outside the notebook.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/unistay.git
cd unistay
````

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Notebook

Open `UniStay.ipynb` using Jupyter Notebook or JupyterLab and run all cells sequentially.

---

## 🧪 Sample Outputs

* Clusters of similar accommodations
* Mapped locations with distance-based suggestions
* User input simulation and nearest cluster prediction


---

## 🎯 Use Cases

* University housing portals
* Student accommodation platforms
* Geo-aware real estate analytics

---
