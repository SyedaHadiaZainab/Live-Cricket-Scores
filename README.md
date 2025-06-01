# 🏏 Live Cricket Score - GUI App

This project is a **desktop application** built using **Python** and **Tkinter** to show **live cricket scores** scraped from [Cricbuzz](https://www.cricbuzz.com). The app provides an interactive GUI that fetches live match data, including team names, match summaries, and current scorecards.

---

## 📌 Features

- ✅ Beautiful Tkinter GUI with background image
- ✅ Live match list with dropdown menu
- ✅ Match summary, header, and scorecard display
- ✅ Real-time refresh of match data
- ✅ Built-in error handling for empty/invalid selections and web scraping failures

---
## 🛠️ Technologies Used

- **Python 3.x**
- **Tkinter** – GUI framework
- **ttk.Style** – Modern widget styling
- **PIL (Pillow)** – Background image handling
- **BeautifulSoup** – Web scraping
- **Requests** – HTTP requests
- **Regex** – Text parsing

---

## 📁 Project Structure

live-cricket-score/
├── IK.webp # Background image for GUI
├── live_score_app.py # Main application code
├── README.md # Project documentation
└── requirements.txt # Python dependencies

## ⚙️ How It Works

1. **Launch GUI:** Opens a Tkinter window with a styled interface.
2. **Fetch Live Matches:** Scrapes [Cricbuzz](https://www.cricbuzz.com) for match listings.
3. **Dropdown Selection:** User selects a match to view live data.
4. **Display Scores:** Shows match header, both teams' scores, and match summary.
5. **Refresh Button:** Reloads live match list from the website.

---

## ▶️ Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/SyedaHadiaZainab/live-cricket-scores.git
cd live-cricket-score
2. Install Dependencies
Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
Install packages:
pip install -r requirements.txt
3. Run the App
python live_score_app.py
⚠️ Make sure you place a valid image at the specified path or update the image path in the code.

📦 Requirements
Add the following to a requirements.txt file:

nginx
Copy
Edit
requests
beautifulsoup4
pillow
🧠 Known Limitations
Relies on Cricbuzz HTML structure — may break if the site updates

No internal caching — matches are refreshed with each request


👩‍💻 Author
Syeda Hadia Zainab
📧 Email: taqviggg@gmail.com
🔗 LinkedIn: syeda-hadia-zainab

📜 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Cricbuzz – for providing live match data

Python Community for all open-source libraries# Live-Cricket-Scores
