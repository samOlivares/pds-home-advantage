# Home Advantage in European Football

Final Programming for Data Science project by Sam Olivares, Shayan Karimi, Etienne Padelo and Kerry Assohoun.

We study how home advantage varies across Ligue 1 and the Premier League, over time and across groups of nearby stadiums during the 2024–2025 season. The notebook compares league outcomes, mines frequent patterns, evaluates a weekly forecast and clusters stadiums geographically.

## Run the project

1. Install the dependencies with `python -m pip install -r requirements.txt`.
2. From this directory, open `Olivares_notebook.ipynb` in Jupyter and run all cells.
3. Open `Olivares_dashboard.html` in your browser. The notebook regenerates this standalone file.

## Files

- `Olivares_notebook.ipynb` — KDD workflow, analyses and dashboard export.
- `Football_PDS_2024-2025_with_stadiums.csv` — 686 matches with coordinates for the 38 usual home stadiums.
- `Olivares_dashboard.html` — charts and tables for the four analyses.
- `Olivares_slides.pdf` — five slides for the presentation and live demo.

## Results and scope

The home–away win gap was 13.7 percentage points in Ligue 1 and 6.1 in the Premier League. The weekly forecast is exploratory because the dataset covers a single season. The raw gap can reflect team strength and the stadium mapping uses each club's usual home ground.

Match data come from [Football-Data.co.uk](https://football-data.co.uk/downloadm.php). Each coordinate source is listed in the CSV. Review the source terms before publicly redistributing the dataset.

## Demo

Define the home–away win gap, compare the two leagues, explain the strongest association rule, compare the forecast and baseline errors, then use the dashboard to show the stadium clusters.
