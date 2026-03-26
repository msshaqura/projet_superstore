🎯 Superstore ETL Dashboard
Hugging Face Spaces Python 3.11+ Streamlit

🚀 Live Demo
👉 Try the app here:
https://huggingface.co/spaces/msshaqura/superstore_project

📝 Description
This project implements an ETL pipeline to load Superstore data from a CSV file, clean it, and create a star schema in PostgreSQL using SQLAlchemy and Pandas.
The app also provides a Streamlit dashboard to visualize key metrics from the Superstore dataset.

🎯 Project Objectives
- Extract, clean, and load Superstore data into PostgreSQL
- Create a star schema for analytics
- Provide an interactive dashboard with Streamlit
- Visualize sales, profit, and other key metrics

📊 Key Features
- Cleaned dataset ready for analysis
- PostgreSQL database integration
- Streamlit interactive dashboard
- ETL automation scripts

🛠️ Technologies Used
- Python 3.11+
- Streamlit – Interactive dashboard
- Pandas – Data manipulation
- SQLAlchemy – Database ORM
- Plotly / Matplotlib / Seaborn – Visualizations
- PostgreSQL – Data warehouse
- Docker – Containerized environment

📁 Project Structure
superstore_project/
│
├─ src/
│  ├─ main.py          # Main ETL script
│  ├─ db.py            # PostgreSQL connection and engine setup
│  ├─ data_loader.py   # Data cleaning and loading
│  └─ streamlit_app.py # Streamlit dashboard
│
├─ data/               # Cleaned CSV data
│  └─ clean_superstore.csv
│
├─ Dockerfile
├─ requirements.txt
└─ README.md

⚙️ Installation (Local)
# Clone the repository
git clone https://huggingface.co/spaces/msshaqura/superstore_project
cd superstore_project

# Create virtual environment
python -m venv venv

# Activate it
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run src/streamlit_app.py

🌐 Deployment
The app is deployed using Hugging Face Spaces (Docker + Streamlit)

🔗 https://huggingface.co/spaces/msshaqura/superstore_project

👨‍💻 Author
GitHub: https://github.com/msshaqura
Hugging Face: https://huggingface.co/msshaqura