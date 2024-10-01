# SentMart: Stock Sentiment and Prediction Platform

## Team Info & Policies (10%)

**Team Members and Roles:**
- **Serena:** Data processing, gathering sources of data, natural language sentiment analysis.
- **Alisiia:** Web scraping, web development/UI.
- **Kevin:** Web scraping, web development/UI.
- **Vanshith:** Data processing, gathering sources of data, time series forecasting, natural language sentiment analysis.
- **Dhriti:** Data processing, gathering sources of data, time series forecasting, natural language sentiment analysis.

**Project Artifacts:**
- **GitHub Repo:** [SentMart Repository](https://github.com/vanshiith/SentMart)

**Communication Channels:**
- Google Meet
- Snapchat
- Google Chat
- Gmail

---

## Product Description (20%)

SentMart is a stock sentiment and prediction platform designed to provide stock trend visualization, sentiment analysis, and AI-based stock predictions. It aims to help users make informed decisions based on both quantitative financial data and qualitative public sentiment.

### Major Features:
1. **Stock Trend Visualization:**
   Displays historical and current stock trends in easy-to-read graphs and charts.
2. **Public Sentiment Analysis:**
   Shows public opinion on selected companies gathered from news articles, social media, and market reports.
3. **AI-Based Stock Predictions:**
   Generates stock predictions using AI algorithms that factor in financial and sentiment data.
4. **Citing Reasons for Predictions:**
   Each prediction is accompanied by references to news articles and reports influencing the forecast.

### Stretch Goals:
1. **Graph Hover Insights:**
   Users can see how the broader market performed during specific periods by hovering over graphs.
2. **Sentiment Change Notifications:**
   Notifies users of significant shifts in sentiment for their selected stocks.

---

## Use Cases (Functional Requirements) (30%)

### Serena: Set Up Alerts
**Actors:** Users interested in receiving alerts for companies they follow.  
**Triggers:** Users subscribe for alerts.  
**Preconditions:** Regular updates on stock/news data.  
**Postconditions:** Users receive well-formatted email/messages with alerts.

**Steps:**
1. User subscribes to company alerts.
2. System verifies preferred alert format (email/SMS).
3. System sends alerts with changes in stock or sentiment.

### Kevin: Login to the Website
**Actors:** Users (traders or investors).  
**Triggers:** Users click the login button.  
**Preconditions:** Users must have a registered account.  
**Postconditions:** System verifies user credentials and grants access to personalized dashboard.

**Steps:**
1. User clicks login.
2. System verifies credentials and two-factor authentication (if enabled).
3. User is logged in and navigates to their dashboard.

### Vanshith: Compare Stocks
**Actors:** Users comparing stocks.  
**Triggers:** User clicks the compare button.  
**Preconditions:** User is signed in and has selected stocks.  
**Postconditions:** User sees forecasts, sentiment, and news for compared stocks.

**Steps:**
1. User logs in and selects stocks to compare.
2. System displays important info (forecasts, sentiment, news) for both stocks.

### Dhriti: Dashboard with Real-Time Forecasts, Historical Trends, Links to Credible Sources
**Actors:** Users (traders or investors).  
**Triggers:** User scrolls to the dashboard.  
**Preconditions:** System has access to news/data.  
**Postconditions:** User views real-time forecasts and credible sources for stock predictions.

**Steps:**
1. User selects stock or portfolio.
2. System displays real-time forecasts, analysis, and links to credible articles.

### Alisiia: New User Sign-In
**Actors:** New user signing up.  
**Triggers:** User accesses the sign-up page.  
**Preconditions:** User has a valid email/phone number.  
**Postconditions:** System successfully creates and verifies the user account.

**Steps:**
1. User enters details.
2. System verifies contact info with a code.
3. User enters preferences and completes profile.

---

## Non-functional Requirements (10%)

1. **Scalability:**  
   The platform should efficiently handle an increasing number of users and data without degrading performance. It must be capable of processing real-time public sentiment from various sources.

2. **Usability:**  
   The platform should be user-friendly, especially for new stock market participants. A clean interface with tutorials and tooltips should make navigation intuitive.

3. **Reliability:**  
   Stock predictions must be accurate and transparent, supported by credible data sources. Users should trust the platform’s output and reasoning.

---

## External Requirements (10%)

1. The product must handle invalid user inputs (e.g., invalid company names) and notify users with appropriate messages.
2. The product will be hosted on a public domain, allowing easy access and use.
3. The codebase will follow clean coding protocols and be well documented for future developers.

---

## Team Process Description (20%)

### Technologies:
- PyTorch/TensorFlow for model building
- NLTK for NLP and sentiment analysis
- OpenAI/VertexAI APIs for prediction
- Streamlit for web development

### Phased Development:
1. **Phase 1 (Data Collection & Database Building):** 10/08/2024
   - Group 1: Web scraping/data gathering.
   - Group 2: Building Database.
   
2. **Phase 2 (Data Preprocessing):** 10/22/2024
   - All members perform different steps in data preprocessing.

3. **Phase 3 (Model Building):** 11/05/2024
   - Group 1: Build the model and compare accuracy.
   - Group 2: Refine data preprocessing based on feedback.

4. **Phase 4 (Model Integration):** 11/12/2024
   - Group 1: Integrate the model into the web platform.

5. **Phase 5 (Deployment):** 11/18/2024
   - Group 2: Deploy the platform.

### Major Risks:
1. Lack of experience with technologies used.
2. Time constraints due to other academic commitments.
3. Difficulty in meeting outside class hours.

### Feedback:
We will seek external feedback after the time series forecasting and sentiment analysis are completed. Input from economics professors and classmates will guide improvements.

---

