# ☀️ Automated Daily Weather Email Notification – n8n

A fully automated workflow built in N8N that delivers personalized daily weather summaries via email. Using the Open-Meteo API, this system fetches real-time forecast data and sends it each morning at 6 AM, helping users start their day with timely weather insights.

---

## 📸 Screenshots

| Workflow | Email Message |
|----------|----------------|


---

## 🧠 Key Features

- ⏰ **Scheduled Delivery**: Automatically runs every day at 6:00 AM.
- 🌤️ **Weather API Integration**: Uses Open-Meteo API to get daily forecast data.
- 🔧 **Custom Data Formatting**: Extracts and formats key weather info like high/low temperatures.
- 📧 **Email Notification**: Sends a clean, concise weather summary via Gmail.
- ✉️ **Personalized Output**: Easy to adjust for different locations or recipients.

---

## 🛠 Tech Stack

- **n8n** – Workflow automation  
- **Open-Meteo API** – Real-time weather data  
- **Gmail Module** – For sending automated emails  
- **JavaScript Code Node** – For custom data processing and formatting  

---

## ⚙️ How It Works

1. **Scheduled Trigger**: Fires daily at 6:00 AM.
2. **Weather Fetch**: Sends a request to Open-Meteo API for the latest weather data (location can be customized).
3. **Data Processing**: A code node extracts and formats key info like the day's high/low temperatures and weather summary.
4. **Email Composition**: The message is built with relevant weather details.
5. **Email Delivery**: Sent using the Gmail module to the target recipient(s).

---


## 📈 Future Improvements

- Add location-based personalization (e.g. use user’s city or GPS)  
- Format email using HTML for improved visual style  
- Send multi-day forecasts or severe weather alerts  
- Integrate with calendar apps or smart devices  

---


