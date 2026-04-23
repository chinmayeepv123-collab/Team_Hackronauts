AquaGuard – Smart Water Quality Monitoring System using AI
# Team_Hackronauts

Description
AquaGuard is an AI-based water quality monitoring system that analyzes water parameters and predicts whether the water is safe or unsafe. It also provides alerts, a water quality score, and AI-based suggestions.

Features
- Water quality prediction (Safe / Unsafe)
- Water Quality Index (WQI)
- Water health score
- Alerts for unsafe conditions
- Smart suggestions
- AI-based water advisor
- Data visualization

Technology Used
- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Plotly
- Groq API 
- Python-dotenv
- LangChain NVIDIA AI Endpoints

Project Structure
AquaGuard-AI/
│── app.py
│── dataset.csv
│── requirements.txt
│── README.md
│── .env (not included in repository)
│── venv/ (ignored)

How to Run
1. Clone the repository

2. Install dependencies:
   pip install -r requirements.txt

3. Run the app:
   streamlit run app.py

Input Parameters
- pH
- TDS
- Turbidity
- Temperature

Output
- Safe / Unsafe prediction
- WQI value
- Health score
- Alerts
- AI suggestions

Future Scope
- Integration with real-time IoT sensors (pH, TDS, turbidity, temperature)
- Wireless data transmission using ESP32 or Arduino
- Cloud-based monitoring and data storage
- Mobile application for remote access
- SMS/Email alerts for critical water conditions
- Advanced AI models for more accurate prediction

Note: 
This project currently uses manually entered values to simulate sensor data. It can be connected to real sensors like pH, TDS, turbidity, and temperature sensors in the future.

# Team Members
- Chinmayee P V
- Chethana S
- Khushi N
- Manaswi R
