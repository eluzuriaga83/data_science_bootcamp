

Google Drive

# 🍽️ Restaurant Social Media Sentiment Analysis - Twitter NLP & Word Cloud
 
## Table of Contents
 
- [Project Overview](#project-overview)
- [Executive Summary](#1-executive-summary)
- [Business Context](#2-business-context)
- [Analysis](#3-analysis)
  - [Word Cloud: Most Discussed Topics](#word-cloud-most-discussed-topics)
  - [Sentiment by Category](#sentiment-by-category)
- [Key Insights](#4-key-insights)
- [Recommendations](#5-recommendations)
  - [Immediate Actions](#immediate-actions)
  - [Strategic Initiatives](#strategic-initiatives)
  - [Long-Term Opportunities](#long-term-opportunities)
- [Methodology](#methodology)
- [Full Analysis](#-full-analysis)
- [Contact](#-contact)
---
 
## Project Overview
 
This project is a data analysis case study focused on a restaurant in Guayaquil, Ecuador that needed to understand customer sentiment and identify growth opportunities from social media—but had no way to analyze unstructured Twitter data at scale.
 
The focus of this project is on **natural language processing, text mining, sentiment analysis, and social network analysis**—core responsibilities of a data analyst role. The end result is a set of clear, actionable business recommendations driven entirely by real customer voices on social media.
 
---
 
## 1. Executive Summary
 
- **Goal:** Analyze Twitter data about a Guayaquil restaurant to uncover customer sentiment patterns, frequently discussed topics, and influencer relationships that inform marketing and service improvement decisions.
- **Key Insights:**
  - Recurring service complaints were identified as primary drivers of negative sentiment
  - Several menu items received consistent positive feedback but lacked marketing exposure
  - A small group of influencer accounts drives a disproportionate share of conversation volume
  - Peak engagement windows were identified, enabling better-timed social media responses
- **Business Impact:** The restaurant now has a data-driven foundation to address service pain points, promote high-performing menu items, engage key influencers, and optimize posting schedules for maximum reach.
---
 
## 2. Business Context
 
**Dataset Overview:**  
This analysis leverages Twitter data collected via the Twitter API with geolocation filtering around Guayaquil, Ecuador, capturing:
 
- Customer tweets mentioning the restaurant (positive, negative, and neutral)
- Spanish-language text requiring specialized NLP preprocessing
- Social network connections between accounts discussing the restaurant
- Temporal patterns of tweet activity
**Why It Matters:**  
For a restaurant, online reputation is everything. Unstructured social media data contains real, unfiltered customer opinions—but only becomes actionable when properly analyzed. Understanding what customers talk about most, how they feel, and who influences the conversation helps restaurant owners make targeted decisions on service, marketing, and customer engagement rather than relying on guesswork.
 
---
 
## 3. Analysis
 
### Word Cloud: Most Discussed Topics
 
*The word cloud visualizes the most frequently used terms in tweets about the restaurant. Dominant words reveal what customers associate most strongly with the brand—both positive themes like food quality and ambiance, and recurring pain points like wait times and service. The larger the word, the more frequently it appeared across all collected tweets.*
 
[![Word Cloud - Most Discussed Topics](https://github.com/eluzuriaga83/data_science_bootcamp/raw/main/Wordcloud/visualizations/discuss_topics.png)](https://github.com/eluzuriaga83/data_science_bootcamp/blob/main/Wordcloud/visualizations/discuss_topics.png)
 
### Sentiment by Category
 
*The sentiment breakdown classifies tweets as positive, negative, or neutral and groups them by topic category. This reveals not just overall sentiment, but which specific aspects of the restaurant experience (food, service, atmosphere, price) drive the most positive or negative reactions—allowing for targeted operational improvements.*
 
[![Sentiment by Category](https://github.com/eluzuriaga83/data_science_bootcamp/raw/main/Wordcloud/visualizations/sentiment_category2.png)](https://github.com/eluzuriaga83/data_science_bootcamp/blob/main/Wordcloud/visualizations/sentiment_category2.png)
 
---
 
## 4. Key Insights
 
✔ **Service Is the Top Complaint Driver:** Negative sentiment clusters heavily around service-related terms (wait times, staff responsiveness), making it the clearest operational priority.
 
✔ **Undermarketed Menu Items:** Several dishes and beverages appear frequently in positive tweets but receive minimal promotion—representing a low-cost, high-impact marketing opportunity.
 
✔ **Influencer Concentration:** A small number of accounts generate a large share of engagement. Proactively building relationships with these users can significantly amplify the restaurant's social reach.
 
✔ **Peak Engagement Windows:** Tweet volume spikes at identifiable times of day and week. Aligning social media responses and promotional posts to these windows maximizes visibility.
 
✔ **Language & Localization:** Spanish-language preprocessing was critical—standard English NLP tools produced noisy results, reinforcing the importance of localized text analysis for regional businesses.
 
---
 
## 5. Recommendations
 
### Immediate Actions
 
1. **Address Service Complaints Directly:**  
   Respond publicly to negative service-related tweets to demonstrate accountability. Assign a community manager to monitor and reply within 24 hours of negative mentions.
2. **Promote High-Sentiment Menu Items:**  
   Create targeted social media posts featuring the dishes that appear most in positive tweets. Pair with customer photo reposts to build authentic engagement.
3. **Establish Peak-Hour Posting Schedule:**  
   Reschedule promotional content to align with identified peak engagement windows to maximize organic reach without additional ad spend.
### Strategic Initiatives
 
4. **Influencer Engagement Program:**  
   Identify and personally reach out to the top 5–10 accounts driving the most conversation. Offer exclusive tastings or early access to new menu items in exchange for authentic coverage.
5. **Sentiment Monitoring Dashboard:**  
   Build a lightweight dashboard to track weekly sentiment scores and keyword trends, so the team can detect reputation shifts before they escalate.
6. **Multilingual NLP Refinement:**  
   Expand the text preprocessing pipeline to better handle Ecuadorian Spanish slang and local expressions, improving classification accuracy for future analyses.
### Long-Term Opportunities
 
7. **Expand to Other Platforms:**  
   Extend the analysis pipeline to Instagram and Google Reviews to get a fuller picture of customer sentiment across all major review and social channels.
8. **Automate Data Collection:**  
   Set up scheduled Twitter API pulls so the dataset refreshes weekly, enabling continuous monitoring without manual effort.
9. **Predictive Reputation Modeling:**  
   With enough historical data, build a model that forecasts sentiment trends based on seasonal events, promotions, or operational changes—enabling proactive rather than reactive reputation management.
---
 
## 📊 Methodology
 
**Data Collection:** Twitter API integration with geolocation filtering targeting Guayaquil, Ecuador; collected tweets mentioning the restaurant over a defined time window.
 
**Text Processing:** Cleaned Spanish-language tweets, removed noise (URLs, mentions, special characters), performed tokenization and stopword removal tailored for Ecuadorian Spanish.
 
**Sentiment Analysis:** Classified tweets as positive, negative, or neutral using NLTK and TextBlob, with manual validation on a sample set.
 
**Visualization:** Generated word clouds and sentiment frequency distributions to surface themes and trends in an accessible, business-friendly format.
 
**Network Analysis:** Mapped conversation patterns and influencer relationships using NetworkX to identify key accounts driving engagement.
 
**Tools Used:** Python (Pandas, NumPy), NLTK, TextBlob, Tweepy, NetworkX, Matplotlib, WordCloud, Jupyter Notebooks
 
---
 
## 📓 Full Analysis
 
[Open Jupyter Notebook →](https://github.com/eluzuriaga83/data_science_bootcamp/blob/main/Wordcloud/project_text_mining_and_social_network_analysis_module.ipynb)
 
---
 
## 📧 Contact
 
**Elena Jones**  
📧 [elcjones@proton.me](mailto:elcjones@proton.me)  
💼 [LinkedIn](https://www.linkedin.com/in/elenajoneslc/)

**This project demonstrates my ability to transform unstructured social media data into strategic business insights—the exact type of analysis that drives customer satisfaction and revenue growth.**
