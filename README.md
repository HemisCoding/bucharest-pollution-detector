# Bucharest Pollution Interpolation

This project aims to estimate air pollution levels in arbitrary locations around Bucharest by interpolating known pollution data. Given a point on a map with known pollution measurements (e.g. CO₂ levels), the model predicts pollution at nearby locations based on:

- Geographical coordinates (latitude & longitude)
- Time of day and date (to factor in traffic patterns)
- Additional features like weather and traffic congestion

Users can interact with a map interface to select a point and get pollution estimations in real time.

## Goals

- Explore different interpolation techniques (Kriging, IDW, GPR)
- Use machine learning models to combine spatial and temporal features
- Build an interactive map tool for querying pollution estimates
- Keep everything open-source and reproducible

## Tech Stack

- Python (NumPy, Pandas, Scikit-learn, GeoPandas)
- JupyterLab (for experiments)
- PyKrige, Scikit-gstat (for interpolation)
- Folium or ipyleaflet (for map-based interaction)
- XGBoost or LightGBM (for ML-based predictions)

---

## License

This project is licensed under the [MIT License](LICENSE).
