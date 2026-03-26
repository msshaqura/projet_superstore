🎯 Superstore ETL Dashboard
Hugging Face Spaces • Python 3.11+ • Streamlit

🚀 Live Demo
👉 Try the app here:  
https://huggingface.co/spaces/msshaqura/superstore_project

📝 Description
This project implements an ETL pipeline to load Superstore sales data from CSV, clean it, and create a star schema in PostgreSQL using SQLAlchemy and Pandas.  
It also provides an interactive Streamlit dashboard to explore key metrics and visualizations.

🎯 Project Objectives
- Extract, clean, and preprocess Superstore CSV data  
- Load data into PostgreSQL with a star schema  
- Create an interactive dashboard with Streamlit  
- Visualize sales performance, profits, and trends by state/product/customer  

📊 Key Insights
| Metric                 | Result                     |
|------------------------|---------------------------|
| Total Orders           | (to be calculated)         |
| Total Revenue          | (to be calculated)         |
| Top Selling Product    | (to be calculated)         |
| Most Profitable State  | (to be calculated)         |
| Customers              | (to be calculated)         |

🛠️ Technologies Used
- Python 3.11+  
- Streamlit – Interactive dashboard  
- Pandas – Data manipulation  
- SQLAlchemy – Database ORM  
- PostgreSQL – Database  
- Plotly – Interactive visualizations  
- Matplotlib / Seaborn – Statistical plots  

📁 Project Structure
superstore_project/
│
├─ app.py # Main Streamlit app
├─ src/
│ └─ streamlit_app.py # Additional code for dashboard
├─ data/
│ └─ clean_superstore.csv # Cleaned dataset
├─ requirements.txt # Python dependencies
├─ Dockerfile # Docker configuration
└─ README.md # Project description


⚙️ Installation (Local)
```bash
# Clone the repository
git clone https://github.com/msshaqura/projet_superstore.git
cd projet_superstore

# Create virtual environment
python -m venv venv

# Activate it
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py

🌐 Deployment
The app is deployed using Hugging Face Spaces (Docker + Streamlit):
🔗 https://huggingface.co/spaces/msshaqura/superstore_project

👨‍💻 Author

GitHub: https://github.com/msshaqura
Hugging Face: https://huggingface.co/msshaqura