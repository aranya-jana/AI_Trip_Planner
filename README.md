# AI Travel Planner

> 🚧 **Project Status: Under Construction**  
> This project is currently in active development. Features, structure, and setup steps may change over time.

---

## Overview

AI Travel Planner is an **Agentic AI-powered** travel planning application designed to help users create intelligent and personalized travel experiences. The system uses autonomous AI agents along with real-time data to generate smart travel recommendations, optimize itineraries, estimate budgets, and automate trip planning workflows.

The project uses `uv` for fast Python package and environment management.



## Features

Plan a trip for any city worldwide using real-time data and Agentic AI-powered recommendations.

### Core Features

1. **Real-Time Weather Information**
   - Get live weather updates for your destination city.

2. **Attractions & Activities**
   - Discover famous tourist attractions and recommended activities.

3. **Hotel Cost Estimation**
   - Estimate hotel prices based on your destination and stay duration.

4. **Currency Conversion**
   - Convert travel expenses into your preferred currency instantly.

5. **Smart Itinerary Planning**
   - Generate day-wise travel plans including:
     - Places to visit
     - Recommended duration of stay
     - Suggested travel schedule

6. **Total Expense Calculation**
   - Estimate the complete travel budget including:
     - Hotels
     - Transportation
     - Activities
     - Food expenses

7. **AI-Generated Travel Summary**
   - Automatically generate a concise travel summary for the entire trip.

8. **Agentic AI Workflow**
   - Autonomous AI agents collaborate to:
     - Collect travel data
     - Analyze destinations
     - Optimize schedules
     - Generate personalized recommendations

---

## Getting Started

### 1. Install `uv`

First, install `uv`:

```bash
pip install uv
```



### 2. Initialize the Project

Create a new project:

```bash
uv init AI_Travel_Planner
```



### 3. Check Installed Packages

View installed Python packages:

```bash
uv pip list
```



### 4. List Available Python Versions

```bash
uv python list
```



### 5. Install Python 3.11.15

Install the required Python version:

```bash
uv python install cpython-3.11.15-windows-x86_64-none
```

Verify installation:

```bash
uv python list
```



### 6. Create a Virtual Environment

Create a virtual environment named `env`:

```bash
uv venv env --python cpython-3.11.15-windows-x86_64-none
```

> ⚠️ If you are using Conda, deactivate it first:

```bash
conda deactivate
```

If needed, recreate the environment using:

```bash
uv venv env --python cpython-3.11.15-windows-x86_64-none
```



### 7. Activate the Virtual Environment

From your project directory, activate the environment:

```bash
your_project_directory\AI_Travel_Planner\env\Scripts\activate.bat
```

After activation, your terminal should indicate that the virtual environment is active.



### 8. Install Dependencies

Example: Install `pandas`

```bash
uv add pandas
```


<!--
## Project Structure

```text
AI_Travel_Planner/
│
├── env/                # Virtual environment
├── pyproject.toml      # Project configuration
├── uv.lock             # Dependency lock file
└── README.md           # Project documentation
```
-->
---

## Requirements

- Python 3.11.15
- uv package manager
- Windows OS (commands above are Windows-specific)

---

## Notes

- Ensure `uv` is installed globally before running commands.
- Use the virtual environment for all development work.
- More features and modules will be added soon.

---

## Future Improvements

- Flight price prediction
- AI chatbot travel assistant
- Google Maps integration
- PDF itinerary export
- Multi-user trip collaboration
- Expense analytics dashboard

---

## Contributing

Contributions, suggestions, and feedback are welcome while the project is under development.
