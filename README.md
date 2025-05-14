# COVID‑19 Global Data Tracker

A lightweight, self‑contained Jupyter Notebook project for exploring global COVID‑19 trends (cases, deaths, vaccinations) using the Our World in Data dataset. All visualizations are interactive—powered by Plotly.

---

## 📂 Repository Structure

Covid Data Tracker Project/
├── covid19_global_data_tracker.ipynb   # Main analysis notebook
├── owid-covid-data.csv                 # Raw data from Our World in Data
├── README.md                           # This file

## 🚀 Getting Started
Follow these steps to clone the repo, install dependencies, and spin up the notebook.

## 1. Clone the repository
   
git clone https://github.com/<your‑username>/covid-data-tracker-project.git
cd covid-data-tracker-project

(Optional) Create & activate a virtual environment
Windows (PowerShell)

python -m venv venv
.\venv\Scripts\Activate
macOS / Linux

python3 -m venv venv
source venv/bin/activate

Install Python dependencies
pip install pandas plotly jupyter
You can also create a requirements.txt with pip freeze > requirements.txt for future installs.

## 💾 Data
The file owid-covid-data.csv is the cleaned CSV snapshot from Our World in Data.

If you ever want a fresh copy, download it here:
https://github.com/owid/covid-19-data/tree/master/public/data

Ensure the CSV sits alongside the notebook in the project root.

## 📓 Running the Notebook
Launch Jupyter:

jupyter notebook
In your browser, open covid19_global_data_tracker.ipynb.

Run cells in order (there’s an “Auto‑install & Imports” cell at the top to pull in missing libraries).

Enjoy interactive charts for:

Total cases & deaths over time (Kenya, U.S., India by default)

Top‑10 countries by cumulative cases

Death‑rate table

Vaccination rollout curves

(Optional) Global choropleth map

Use the Narrative section at the bottom to record your key insights.

## 🔧 Customization
Countries
Edit the countries = [...] list in Cell 2 to track any set of locations you prefer.

Data path
By default the notebook reads owid-covid-data.csv from its own folder.
To point elsewhere, update the csv_path = Path(...) in Cell 1.

Additional analyses
Feel free to add new charts, correlate with population data, or export as PDF/HTML.

## 🤝 Contributing
Fork the repo

Create a feature branch (git checkout -b feature/my-new-chart)

Commit your changes (git commit -am "Add my new chart")

Push to your branch (git push origin feature/my-new-chart)

Open a Pull Request and describe your improvements

## 📜 License
This project is released under the MIT License. See LICENSE for details.

Happy analyzing!
