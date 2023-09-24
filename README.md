# Codeforces_Tracker

Codeforces Tracker is a Python script that generates and updates graphical representations of your Codeforces profile data, including problems solved by rating and your rating history.

## Prerequisites

Before running the script, make sure you have the following installed:

- Python (version 3.11 recommended)
- Required Python packages (install using `pip install -r requirements.txt`)

## Usage

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/Codeforces_Tracker.git

2. Navigate to Project Directory:

   ```bash
   cd Codeforces_Tracker

3. Run the Script:

      ```bash
      python codeforces.py
      ```
   This will generate graphical charts of your codeforces profile data and save them in their respective directory.

4. To automatically update and push these images to your GitHub profile, set up GitHub Actions:
      - Refer yml file to understand workflow
      - Make your own PAT key and save it as secrets and access it for security purpose.


## Directory Structure

The project directory contains the following files and directories:

- 'codeforces.py': The Python script for fetching and visualizing Codeforces data.
- 'requirements.txt': A list of Python packages required by the script.
- '.github/workflows/main.yml':  GitHub Actions workflow for automating updates to your GitHub profile.
- 'Contest_Rating': Directory to save my daily contest rating graph.
- 'Problem_solved': Directory to save my Problem solving graph according to problem rating.
- 'Latest_Info': A special directory to overwrite my latest graph images so, I can use it to show over my profile.


## Github Actions

GitHub Actions are set up to run the script and update your GitHub profile with fresh images daily. Make sure to configure your GitHub repository secrets for authentication.


## Output

![Latest Problems Graph](https://github.com/CoderInTheNorth-049/Codeforces_Tracker/blob/main/Latest_Info/contest_rating_graph.png)
![Latest Rating Graph](https://github.com/CoderInTheNorth-049/Codeforces_Tracker/blob/main/Latest_Info/solved_problems_graph.png)


## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/CoderInTheNorth-049/Codeforces_Tracker/blob/main/LICENSE) file for details.

