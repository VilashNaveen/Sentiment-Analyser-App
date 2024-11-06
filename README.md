# ABSA for Product Improvement

## Aspect-Based Sentiment Analysis for Product Insights

This repository implements Aspect-Based Sentiment Analysis (ABSA) on user reviews from e-commerce platforms. The project aims to deliver valuable insights for product enhancement using advanced natural language processing (NLP) techniques and an intuitive user interface.

### Key Features

1. **Product Portfolio Management**
   - Add, manage, and track multiple products for review analysis.
   - Organize products efficiently for comparative insights.

2. **Web Scraper**
   - Automatically collect customer reviews from various e-commerce platforms.
   - Configure scraping parameters for specific data sources.

3. **Sentiment Analysis**
   - Utilizes a fine-tuned BERT model for token classification in ABSA tasks.
   - Extracts product aspects and associated sentiments from user reviews.

4. **Insightful Reporting**
   - Generate visual data reports with graphs and charts.
   - LLM-powered text generation for detailed product improvement insights.
   - Customizable reports to focus on specific aspects or sentiment trends.

---

### Technology Stack

- **Backend**: Node.js, Flask API
- **Frontend**: React
- **Machine Learning**: BERT, Hugging Face Transformers
- **Web Scraping**: Beautiful Soup

---
### Getting Started on Frontend

- ( See deployed [Frontend](https://analytica-ten.vercel.app/))

- As a prerequisites you should have a `React` compatible environment

To get started with the Frontend, follow these steps :

1. Clone this repository.

2. cd in to the project directory and Install the dependencies using following command.(Activate the Virtual Environment if you are using one. It's recommended to use one.)
> npm install

3. See [Sample environment](https://github.com/luckylukezzz/Sentiment-Analyser-Frontend/blob/main/.env_sample) file and change your `.env` file accordingly

4. Start the Frontend using following command.
> npm start

---

### Getting Started on Backend Server

- As a prerequisites you should have a `JavaScript` compatible environment

To get started with the Frontend, follow these steps :

1. Clone this repository.

2. cd in to the project directory and Install the dependencies using following command.(Activate the Virtual Environment if you are using one. It's recommended to use one.)
> npm install

3. See [Environment Variables](https://github.com/luckylukezzz/Sentiment-Analyser-Backend/blob/main/.env_sample) file sample and
change your `.env`file accordingly

4. Start the Backend Server using following command.
> npm start

---

### Getting Started on FlaskApp


**flaskapp extracts reviews from E-Commerce platforms and fills database with processed Info**

#####  As a prerequisites you should have following
- your `mysql` environment set up and server running.
- Python environment with `Python version 3.12` or higher

To get started with the Frontend, follow these steps :

1. Clone this repository.

2. cd in to the project directory and Install the dependencies using following command.(Activate the Virtual Environment if you are using one. It's recommended to use one.)

```
pip install -r requirements.txt
```

3. create `.env` file inside the directory including following environmental variables.
(You are supposed to update variable values according to your sql environment, see [***Sample database***](https://github.com/luckylukezzz/Sentiment-Analysier-flaskapp/blob/main/temp_db_cons/db_aaacae_dse_8_12_2024.sql) for database structure. 
You can simply copy the text below, modify it and save at the specified path as a `.env` file.)

```
HOST= <hostname>
USER= <username>  
PASSWORD= <password>
DATABASE= <database>
```

4. Start the Frontend using following command.

```
python test.py
```

---

### Contributing

We welcome contributions to enhance the functionality and efficiency of our system!.

### About 

This project was created as part of a 5th semester university project under the 
Data Science module in the Department of Computer Science and Engineering at the University of Moratuwa