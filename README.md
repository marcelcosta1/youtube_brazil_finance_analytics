# Analyzing the Brazilian Finance Community on YouTube: A Data Analyst's Exercise Project

## Introduction
As a Marketing Data Analyst, I'm always looking for opportunities to refine my skills and explore new analytical techniques. This project was born out of that desire, combined with a personal interest in the rapidly growing finance community on YouTube in Brazil.

My goal was to:
- Create a personalized database
- Extract relevant insights
- Practice data visualization
- Answer meaningful business questions
- Explore how artificial intelligence could enhance productivity and learning throughout the process

## Project Conception and Objectives
The finance topic was chosen due to my past experiences and the significant growth of the Brazilian financial content creator scene. Instead of focusing on complex code or elaborate visuals, I aimed to keep things simple and concentrate on relevant business questions. The main steps I followed were:

1. **Topic and Idea Conception**
   - Brainstorm tools and approaches to achieve the objective
   - Organize the project in Notion, creating tasks, sub-tasks with statuses, and deadlines (using a scrum approach)

2. **Data Extraction and Cleaning**
   - Build the code to extract information from the YouTube API
   - Clean the extracted data (initially over 149,000 rows)

3. **Data Analysis**
   - Create relevant business questions based on the dataset
   - Develop a Python notebook, breaking it down by business question
   - Write code to generate graphs or tables to answer each question
   - Register the main findings

4. **Data Visualization and Reporting**
   - Create a Power BI dashboard for visualization and deep dives into channel statistics
   - Consolidate findings, document results, and share with the community

## Data Extraction and Cleaning
### Data Extraction
The primary goal was to interact with the YouTube API to retrieve information about various channels and their videos. The Python code extracts data such as:
- Subscribers
- Videos
- Playlists
- Video name
- Length
- Title
- Duration
- Post time
- Likes count

The code selects channels using user-defined keywords to filter for relevant channels.

### Data Cleaning
Since the channels were chosen by keywords, some were not strictly related to finance and needed to be excluded. The cleaning process was the most time-consuming part of the project. Fortunately, the remaining data was well-structured, with few duplicates or missing information.

## Data Analysis: Key Questions and Findings
### Popularity and Engagement
#### What are the most viewed finance-related videos and channels?
- The most viewed videos often included ads and shorts.
- Some videos from large channels, like *Mulheres que Mudam o Mundo: Zica Assis* and *A História de Jó (Rodrigo Silva) | PrimoCast 241,* ranked high, even though their direct connection to finance wasn't immediately obvious.

#### What types of finance topics generate the most engagement?
To address this, I faced two main challenges:
1. Grouping videos by topic based on their titles
2. Creating an engagement metric

I developed a script that tokenized video titles, analyzed them word by word, and categorized them based on a list of keywords. Then, I created an "Engagement" column using the formula:

**Engagement = [Number of views + (# Likes x 4) + (# Comments x 8)] / 100000000**

- **Investing videos had the highest engagement.**
- Surprisingly, the "Misc" category (topics like *Milhas, Política, Crise*) outperformed entrepreneurship and budgeting.

### Trends Over Time
#### How has the popularity of finance-related content changed over time?
- The number of finance-related videos has increased dramatically over the past 10 years.
- There was significant growth in content creation in 2019 (56% compared to 2018) and between 2021 and 2022 (64.4%).
- However, the growth between 2023 and 2024 slowed to around 8%.

#### What seasonal trends can be observed in finance-related video views and engagement?
- Video postings are lower in the first half of the year (28.6% less than in Q3 and Q4).
- February tends to have fewer views, likely due to fewer days and the Carnival holiday.
- There's a notable drop in June, possibly related to the *Festa Junina* celebrations in Brazil.
- The second half of 2022 saw the highest engagement, with a peak in April and May 2024 driven by a large ad campaign from XP Inc.

### Audience Preferences
#### What video titles or keywords are associated with higher engagement?
The keywords with the highest engagement include:
- **Dinheiro (Money)**
- **Investir (Invest)**
- **Renda (Income)**
- **Investimentos (Investments)**
- **Rico (Rich)**

#### Which channels or creators dominate the finance-related niche?
Top channels by total views:
1. **Me Poupe!**
2. **O Primo Rico**
3. **Bruno Perini - Você Mais Rico**

#### Which keywords or phrases appear most frequently in high-performing video titles?
Common high-performing keywords include:
- **dinheiro**
- **investir**
- **ações**
- **renda**
- **investimentos**

## Insights for Creators and Marketers
#### What are the emerging trends in finance-related topics based on recent uploads?
- In the past 60 days, the major trends in finance-related videos were:
  - **Dollar and Bitcoin**
  - **Day Trade**
  - **Ações (Stocks)**
  - **FII (Real Estate Funds)**

### Deep Dive into Main Channels
#### Top 5 Channels by Total Engagement
| Channel | Videos | Views | Engagement | Comments | Top Video |
|---------|--------|--------|-------------|------------|-----------------|
| Me Poupe! | 1689 | 571M | 7.75M | 1M | "Mulheres Que Mudam o Mundo" |
| O Primo Rico | 1064 | 433M | 5.86M | 998K | "COMO GANHAR R$1.500" |
| Bruno Perini - Você MAIS Rico | 2025 | 423M | 5.61M | 453K | "CASO GRAVE SOLUCIONA…" |
| PrimoCast | 2603 | 225M | 2.73M | 234K | "A HISTÓRIA DE JÓ (Rodrigo Silva)" |
| Economista Sincero | 2718 | 193M | 2.82M | 1M | "PRESSÃO NA COCA-COLA…" |

## Conclusion
This project provided valuable insights into the Brazilian YouTube finance community. It highlighted:
- The importance of **data cleaning**
- The power of **engagement metrics**
- The evolving trends in **content creation**

Furthermore, it demonstrated how AI can be a valuable tool for **data analysis**, enhancing both productivity and learning. By focusing on relevant business questions and leveraging **data visualization techniques**, I was able to extract actionable insights valuable for both **content creators and marketers** in the finance niche.

---
### 🚀 Next Steps
- Automate data extraction and update analysis regularly.
- Expand analysis to **regional differences** within Brazil.
- Incorporate **machine learning models** for engagement prediction.

📢 **Feedback and contributions are welcome!** Let's explore data together. 🤓📊

