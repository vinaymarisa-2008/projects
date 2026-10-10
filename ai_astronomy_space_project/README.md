# AI in Astronomy and Space

An educational website built with **Python, Flask, NumPy, HTML, and CSS**. It demonstrates how AI can help astronomers detect exoplanets, classify galaxies, and support space missions.

## Features

- All eight Solar System planets, sorted by average distance from the Sun
- Sort controls for distance, number of moons, or planet name
- Planet cards generated with a Python function and loop
- NumPy calculations for approximate distance in astronomical units (AU), orbital period, sunlight travel time, and visual distance bars
- A simulated exoplanet transit light curve and an introductory AI fact box
- Responsive, space-themed styling

## Requirements

- Python 3.10 or newer recommended
- pip

## Run locally

### 1. Extract the ZIP and open the project folder

```bash
cd ai_astronomy_space_project
```

### 2. Create and activate a virtual environment

**Windows PowerShell**
```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**Windows Command Prompt**
```bat
python -m venv .venv
.venv\Scripts\activate.bat
```

**macOS / Linux**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Start the server

```bash
python app.py
```

Open **http://127.0.0.1:5000** in your browser. Stop the server with `Ctrl+C`.

## Project structure

```text
ai_astronomy_space_project/
├── app.py
├── templates/
│   └── index.html
├── static/
│   └── style.css
├── requirements.txt
├── README.md
├── LICENSE
├── CONTRIBUTING.md
└── .gitignore
```

## Python concepts demonstrated

- **List of dictionaries:** stores planet name, distance, moon count, and display color.
- **`sorted()` and `lambda`:** sort planet data by distance, moons, or name.
- **Functions and loops:** calculate derived values and generate each planet card.
- **NumPy:** vectorized calculations for approximate orbital period and sunlight travel time.
- **Flask:** serves the website and passes data into the Jinja HTML template.

## Notes on scientific accuracy

Distances are approximate average distances from the Sun. Moon counts can change as new moons are confirmed; counts included here are reference values and may become outdated. The light curve is **simulated educational data**, not a live telescope observation. The simplified transit detector illustrates the idea and is not a validated exoplanet-discovery system. Orbital-period values use a simplified Kepler relationship.

## License

Released under the MIT License. See [LICENSE](LICENSE).
