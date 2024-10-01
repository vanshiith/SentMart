1. Team info & policies (10%)
Provide a concise summary of the project team and project artifacts. Specifically:
List each team member and their role in the project.
Serena - data processing, gathering sources of data, natural language sentiment analysis
Alisiia - web scraping, web development/UI
Kevin - web scraping, web development/UI
Vanshith - data processing, gathering sources of data, Time series forecasting, natural language sentiment analysis
Dhriti - data processing, gathering sources of data, Time series forecasting, natural language sentiment analysis
Link to each project relevant artifact such as your git repo (this can be empty for now).
https://github.com/vanshiith/SentMart
List communication channels/tools (e.g., Slack)
Google Meet, Snapchat, Google Chat, Gmail.


2. Product description (20%)
Use the product description of the project proposal as a starting point. Revise it based on feedback you received so far, and incorporate it into this section. Additionally, add the following to this section:
4+ major features you will implement.
Stock Trend Visualization:
The platform will show the historical and current stock trends of selected companies in easy-to-read graphs and charts, helping users track performance over time.
Public Sentiment Analysis:
The platform will display overall public opinion about the company, gathered from sources like news articles, social media, and market reports, providing insight into how the company is perceived by the public.
AI-Based Stock Predictions:
The platform will generate stock predictions based on AI algorithms that factor in both quantitative financial data and qualitative sentiment data. These predictions will give users actionable insights into the potential future performance of stocks.
Citing Reasons for Predictions:
Each prediction will be accompanied by references to the most talked-about news articles and financial reports that influenced the forecast. This feature ensures transparency, allowing users to see exactly why a prediction was made.
2+ stretch goals you hope to implement.
Graph Hover Insights:
Users will be able to see how the broader market performed during specific periods by simply hovering over the stock trend graphs. This contextual data will give users a better understanding of how their selected stocks performed in relation to the market.
Sentiment Change Notifications:
Users will be notified if there are significant shifts in sentiment for the stocks they are monitoring. This feature will help users stay informed of sudden changes in public opinion, allowing them to react quickly.




The major features should constitute a minimal viable product (MVP).
3. Use Cases (Functional Requirements) (30%)
Each team member must come up with and describe at least one use case of your product, following this template:
Serena: Set up alerts
Actors: users who want to get an alert on their focusing companies
Triggers: users subscribe to get alerts of companies they need
Preconditions: Get news/stocks information updating all the time so users can get their alerts right on time
Postconditions (success scenario): Get permission from users to send them alerts either by emails or messages. Also send them a well formatted email/message.
List of steps (success scenario):
A user subscribes to the alert of certain companies.
Make sure how the user ge the alert (email or message or both).
If there are any huge changes on the company’s stock or sentiments, process an alert.
Send the email/message with the company’s name, and the message of changes happening within the company.
Extensions/variations of the success scenario: Users will be able to get the most recent changes on companies they are paying attention to. They can go and check the news or change their holds.
Exceptions: failure conditions and scenarios: Companies refuse to provide data; the news are faked but lead to a lot of sentiments; fail to send alerts to users.


		Kevin- login to the website
Actors: users (traders or investors)
Triggers: users will click login button		
Preconditions:
User already has a registered account
User must remember username and password
Postconditions (success scenario): 
System will check username and password in database
If correct, the user is logged in
The user now can now log in and is able to access any features or personal information
List of steps (success scenario):
user enters the platform’s URL in their browser or clicks on a “Login” button on the homepage
User enters username and password
System checks username and password in database
User has the option of two-factor authentication
System verifies and user is logged in
Users are taken to a personalized dashboard where they can view stock trends, forecasts, and other platform features.
User can now navigate and use the platform and its features
Extensions/variations of the success scenario:  user is able to login as many times they want using the correct username/password and the platform supports the country or region
Exceptions: 
a)User fails to provide a valid email/phone number, leading to a failure in verification.
b)The confirmation email or SMS is delayed, causing user frustration.
c)System experiences downtime, preventing account creation.
d)User's chosen password does not meet security requirements or the user forgot the password, requiring a password reset.
e)If the platform doesn’t support a specific country or region, sign-up may be restricted.




Vanshith: compare stocks
Actors: Anyone who wants to compare stocks before making a financial decision
Triggers: User can hit the compare button and choose the stocks of their choice.
Preconditions: signed in and has a stock to compare with displayed on the dashboard
Postconditions (success scenario): User is able to see both the companies’ forecasts, sentiments, and news that caused the sentiments, and the possible prediction
List of steps (success scenario): The user logs in, user chooses a stock to look at, the user wishes to compare, they hit the compare button, choose a stock to compare, the user gets all the important information with the prediction.
Extensions/variations of the success scenario: user able to choose multiple stocks for comparison, a dedicated page to perform comparisons, give an overall AI analysis of the current and future prospects of the stock.
Exceptions: failure conditions and scenarios: Overfitting and incorrect predictions/comparisons, do not have enough information for comparison.


Dhriti: dashboard with real time forecasts, historical trends, links to credible sources
Actors: users (traders or investors)
Triggers: scroll towards the dashboard and hover cursor over it
Preconditions: signed in, is on the page for a particular company (for example AAPL), the system has access to credible and relevant sources news and data
Postconditions (success scenario): The user can view stock forecasts on their dashboard along with clickable links to credible articles or reports that support the forecast or sentiment analysis.
List of steps (success scenario): 
User selects a stock or portfolio they wish to review in more detail
The system displays the real time forecasts, including sentiment analysis, prediction graphs, links to articles etc.
For each stock, the system displays links to credible news articles or financial reports from credible sources (e.g., articles from Bloomberg, Reuters, or official financial filings)
The links to the articles are clickable and take the user to the particular article
Based on the predictions and the articles, the user feels enabled to make a more informed decision
Extensions/variations of the success scenario: 
User is able to see dashboards for their personal portfolio, their starred stocks, and is also able to look up companies and see their performance.
User is able to set up notifications on the dashboard
Exceptions: failure conditions and scenarios: 
No credible sources available (no recent news, no news articles from credible sources etc.). → the system displays an error message “no recent news articles available”
A lot of sources → maybe rank the sources and display the top 30 articles 
Failure to display real time data → display an error message “system down, try again later”














Alisiia: new user sign in
Actors: 
User: A prospective trader or investor.
System: The stock forecasting platform.


Triggers: 
User wants to access stock forecasting features and decides to sign up for the platform.


Preconditions: 
User must have access to the platform’s website.
User has access to a valid email address or phone number for verification.
System has a user registration feature implemented and functional.


Postconditions (success scenario): 
The system successfully creates a new user account and allows the user to log in.
The user is guided to set up their profile and preferences for stock forecasts.




List of steps (success scenario): 
User accesses the platform’s sign-up page.
User enters required details such as name, email/phone number, and password.
The system verifies the email or phone number by sending a confirmation code.
User enters the verification code to confirm their contact information.
User completes additional profile information such as preferred industries (e.g., recycling industry), risk tolerance, and notification preferences.
System stores the user's data and preferences.
The user is automatically logged in and welcomed with an introductory tutorial or dashboard overview.
User can now explore and use the platform's forecasting features.


Extensions/variations of the success scenario: 
User can sign up using social media accounts like Google or Facebook for quicker registration.
System offers optional two-factor authentication (2FA) for enhanced security.
System provides personalized onboarding based on the user's selected preferences.


Exceptions: failure conditions and scenarios: 
User fails to provide a valid email/phone number, leading to a failure in verification.
The confirmation email or SMS is delayed, causing user frustration.
System experiences downtime, preventing account creation.
User's chosen password does not meet security requirements, requiring a password reset.
If the platform doesn’t support a specific country or region, sign-up may be restricted.


(At the end of this step you will have at least one use case per team member.)
4. Non-functional Requirements (10%)
Describe at least three non-functional requirements, e.g., related to scalability, usability, security and privacy, etc.


Scalability:
The platform must handle an increasing number of users and data sources without performance degradation. This includes the ability to measure and process public sentiment accurately from various channels (social media, news outlets, financial reports) as the user base and stock coverage grow. Success will be measured by how effectively the platform can manage large volumes of real-time data and consistently assess whether public opinion trends positively or negatively impact stock predictions.
Usability:
The platform should be intuitive and user-friendly, especially for those new to the stock market. This includes a clean, guided onboarding process with tutorials and tooltips to help users quickly understand how to navigate the platform. A dashboard with simplified forecasting options, visual aids (charts, graphs), and easy-to-follow steps for executing trades will enhance usability. Success can be measured by user feedback and time taken for new users to complete key tasks like setting up an account or making their first forecast.
Reliability:
The platform must provide clear and trustworthy stock predictions, supported by transparent data sources. This includes citing the specific financial documents, sentiment data, and other relevant factors used in making predictions. Users should be able to see the reasoning behind forecasts and trust that the platform operates on verified data. Success can be measured by maintaining consistent accuracy in predictions and offering clear attributions for the data used, leading to higher user trust and satisfaction.


5. External Requirements (10%)
In addition to the requirements stated above, the course staff imposes the following requirements on your product:
The product must be robust against errors that can reasonably be expected to occur, such as invalid user input.
If the user is putting in an invalid company or companies that we do not have data on them. Show a small window that says “invalid company/information not found”.
The product must be installable by a user, or if the product is a web-based service, the server must have a public URL that others can use to access it. If the product is a stand-alone application, you are expected to provide a reasonable means for others to easily download, install, and run it.
The product will be a web-based service. We plan to obtain a domain and host it on a rented server.
The software (all parts, including clients and servers) should be buildable from source by others. If your project is a web-based server, you will need to provide instructions for someone else setting up a new server. Your system should be well documented to enable new developers to make enhancements.
We will use clean code protocols and detailed description to make sure it is easy to read and understand our code.
The scope of the project must match the resources (number of team members) assigned.
We are planning to scale down the project to one market/firm, which will make the project attainable. If the initial phases of the project go well, we can consider scaling up.
Make sure that these requirements, if applicable to your product, are specialized to your project and included in your document—do not copy and paste these requirements verbatim. You may leave this as a separate section or fold its items into the other requirements sections.
6. Team process description (20%)
Describe your quarter-long development process.
We will be using pytorch/tensorflow for building the models, nltk for NLP, particularly sentiment analysis, an integration of openai/vertexai api for prediction, and streamlit to build the website
Serena - data processing, gathering sources of data, natural language sentiment analysis. → Finished database capstone last semester and did some research with AI generated text during summer.
Alisiia - web scraping, web development/UI- i’ve created several projects that incorporates web scraping and designing UI/UX, therefore I am interested in contributing to this part of the project.
Kevin - web scraping, web development/UI- First time having the opportunity to web scrape and will enjoy doing Sentiment analysis on one of my favorite social media apps, Twitter.  
Vanshith - data processing, gathering sources of data, Time series forecasting, natural language sentiment analysis → Interest in ML, worked on projects, has experience and is willing to learn.
Dhriti - data processing, gathering sources of data, Time series forecasting, natural language sentiment analysis
We shall work in phases. The above task distribution is going to be what each team member wants to specialize in, and to follow a agile methodology we will need to constantly work on the project through all the phases. 
Phase 1: Data Collection and Database Building
Phase 2: Data Preprocessing
Phase 3: Building the model
Phase 4: Integrating the model with Streamlit
Phase 5: Deployment
Provide a schedule for each member (or sub-group) with at least four concrete milestones and deadlines for the quarter.
Phase 1: 10/08/2024
Group 1: Web scraping/data gathering
Group 2: Building Database
Phase 2: 10/22/2024
All perform different steps of data pre-processing the data
	Phase 3: 11/05/2024
Group 1: Work on building the model and compare the accuracy
Group 2: take feedback from group 1 and make necessary changes to the data pre-processing phase
	Phase 4: 11/12/2024
Group 1: understand the code and integrate it with streamlit to build a website
	Phase 5: 11/18/2024
		Group 2: deploying the completed project
Specify and explain at least three major risks that could prevent you from completing your project.
Lack of knowledge or experience in the technologies used. 
Shortage of time to finish up with the assigned duties.
Harder to meet beyond class as all are either Juniors or Seniors with other commitments.
Describe at what point in your process external feedback (i.e., feedback from outside your project group, including the project manager) will be most useful and how you will get that feedback. 
The initial user feedback was provided at the initial stage of the project, by communicating with economics professors regarding scalability of the project as well as we are looking forward towards getting feedback from classmates when were are done with the time series forecasting as well as language sentiment analysis.



