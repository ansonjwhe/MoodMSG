# MoodMSG

<div align="center">
  <h3>🎭 Sentiment Analysis for Discord Messages</h3>
  <p>A full-stack Discord bot and web application that analyzes message sentiment using Google Cloud NLP</p>
</div>

---

## 📋 Overview

MoodMSG is an intelligent Discord bot that reads user messages and analyzes sentiment using Google Cloud's Natural Language API. Users can track their emotional patterns through an interactive web dashboard that visualizes their past messages and sentiments over time.

### Key Features
- 🤖 **Real-time Discord Bot** - Analyzes messages as they're sent in channels
- 📊 **Sentiment Analysis** - Uses Google Cloud NLP for accurate emotion detection
- 📈 **Data Visualization** - Interactive charts showing sentiment trends
- 🎭 **Sentiment Tracking** - View historical message data and mood patterns
- 🎨 **Modern Web UI** - Beautiful React-based dashboard

---

## 🛠️ Tech Stack

### Discord Bot
- **Language**: Python 3
- **Framework**: Discord.py
- **NLP**: Google Cloud Natural Language API
- **Data Processing**: Pandas, NumPy, Matplotlib
- **Database**: MongoDB
- **APIs**: Tenor API

### Web Application
- **Frontend**: React, Redux
- **UI Framework**: Ant Design, React Bootstrap
- **Backend**: Node.js, Express
- **Database**: MongoDB (via Mongoose)

---

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- Node.js 14+
- MongoDB database
- Google Cloud account with Natural Language API enabled
- Discord Bot token
- Tenor API key (optional)

### Installation

#### 1. Clone the repository
```bash
git clone https://github.com/yourusername/MoodMSG.git
cd MoodMSG
```

#### 2. Set up Discord Bot
```bash
# Install Python dependencies
pip install -r requirements.txt

# Create a .env file
touch .env

# Add your credentials to .env
echo "token=YOUR_DISCORD_BOT_TOKEN" >> .env
echo "tenorkey=YOUR_TENOR_API_KEY" >> .env
```

#### 3. Set up Google Cloud
```bash
# Download your Google Cloud service account key
# Save it as cred.json in the root directory
```

#### 4. Set up Web Application
```bash
# Install server dependencies
cd server
npm install
cd ..

# Install client dependencies
cd client
npm install
cd ..
```

#### 5. Configure MongoDB
Update the MongoDB connection string in `bot.py` with your credentials.

### Running the Application

#### Start the Discord Bot
```bash
python bot.py
```

#### Start the Backend Server
```bash
cd server
node index.js
```

#### Start the Frontend
```bash
cd client
npm start
```

The web application will be available at `http://localhost:3000`

---

## 📖 Usage

### Discord Commands
- The bot automatically analyzes messages in Discord channels
- Check your sentiment history on the web dashboard

### Web Dashboard
- View your message history
- See sentiment trends over time
- Explore interactive visualizations

---

## 🎯 Project Journey

### The Challenge
Creating our first Discord bot with NLP integration, while also building a full-stack application—all within a tight 36-hour timeframe.

### Accomplishments
- ✅ Successfully integrated Google Cloud NLP for sentiment analysis
- ✅ Built a working Discord bot from scratch
- ✅ Created a full-stack web application with data visualization
- ✅ Completed the project on schedule despite taking 2 hours to finalize the idea
- ✅ Collaborated effectively in a remote team setting

### Lessons Learned
Our team explored new technologies and strengthened weak areas:
- Python development for some team members
- React and Redux for frontend development
- MongoDB for data persistence
- BeautifulSoup for web scraping
- NLP API integration

---

## 🔮 Future Enhancements

- [ ] User authentication and route security
- [ ] Cloud deployment (Heroku/AWS/DigitalOcean)
- [ ] Expanded statistics and analytics
- [ ] Enhanced UI/UX improvements
- [ ] Multi-server support
- [ ] Customizable sentiment categories
- [ ] Message filtering and privacy controls

---

## 📄 License

ISC

---

## 👥 Contributors

Built with ❤️ by the MoodMSG team during a hackathon

---

<div align="center">
  <p>Made during a 36-hour hackathon</p>
  <sub>Analyzing emotions, one message at a time 🎭</sub>
</div>
