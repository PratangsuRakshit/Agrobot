# Agrobot

## What's Agrobot?
Agrobot is a Python project using Ursina Engine for the GUI. It checks the current demand for crops using Google Trends and predicts future demand with sklearn's Linear Regression.

## How to Get Started
1. **Clone the Repository:**
   ```
   git clone https://github.com/your-username/agrobot.git
   cd agrobot
   ```

2. **Install Dependencies:**
   ```
   pip install -r requirements.txt
   ```

3. **Run Agrobot:**
   ```
   python main.py
   ```

4. **Explore the GUI:**
   Open your web browser and go to `http://localhost:8000` to interact with Agrobot.

## Using Agrobot
1. **Check Current Demand:**
   - See the current demand for a specific crop by selecting it in the GUI.

2. **Predict Future Demand:**
   - Use Linear Regression to predict future demand based on historical data.

## How to Contribute
Got ideas? We'd love your help. Open an issue or pull request on GitHub.

## What I Used
- **Python:** The backbone of Agrobot, offering versatility and ease of use.
- **Ursina Engine:** Powers the graphical user interface, making Agrobot interactive and user-friendly.
- **sklearn:** Employs the Linear Regression model for predicting future crop demand.
- **pandas:** Handles data manipulation and analysis efficiently.
- **numpy:** Adds numerical computing capabilities to the project.
- **urllib3, pytrends, requests:** Essential for fetching and handling data from Google Trends.
- **os, json:** Facilitates interaction with the operating system and handling JSON data.

## License
MIT License - see [LICENSE](LICENSE) for details.
