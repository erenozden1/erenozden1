# Eren Özden

Second-year Computer Science student at UCL, based in London.

I’m interested in problems where maths meets something I care about — especially sport, markets, and data-driven products. I like building systems that turn messy real-world information into something useful, interpretable, and actually usable.

## Contact

- Email: erenozden.uk@gmail.com
- LinkedIn: https://www.linkedin.com/in/ozden-eren

## Education

- UCL — BSc Computer Science (2025–present)
- Robert College, Istanbul (2020–2025)

## About me

- Interested in machine learning, quantitative analysis, and product-building
- Background in software development, data analytics, web apps, and startup-style experimentation
- Passionate about building things that are useful, not just impressive
- Get easily jealous if I am not the best tennis-player in the room

## Featured projects

### Transfer Scout
Transfer Scout is a machine-learning project that tries to estimate what a footballer is actually worth, rather than relying only on transfer-market values that are often slow, crowded, and noisy. The core idea was to build a model that learns from player performance, context, and structural information so that its outputs are more grounded in real footballing value.

What I used:
- Python for the full pipeline
- pandas and NumPy for data cleaning and manipulation
- scikit-learn for preprocessing and evaluation
- LightGBM and XGBoost for model training
- Flask for the web app backend
- Render for deployment

Project link: [https://transferscout.onrender.com/](#)

### The importance of tennis points
This project was a summer research piece focused on measuring how much each point in a tennis match really matters. The goal was to move beyond intuition and quantify the importance of points by linking game state to the probability of winning the entire match.

What I used:
- Python for the analysis pipeline
- NumPy and pandas for computation and data handling
- Matplotlib for visualisation
- Excel for quick exploratory analysis and reporting
- Markov modelling to represent tennis scoring as a probabilistic state system

Project link: [https://tennis-point-importance.netlify.app/](#)

### Replicate AI
Replicate AI was a startup project I co-founded with the idea of building personalised chatbots for online creators. The goal was to create an assistant that could speak in a creator’s voice and answer questions based on the creator’s own content rather than a generic persona.

What I used:
- Python for data processing and model experimentation
- PyTorch-based workflows for fine-tuning and inference
- Prompt engineering and retrieval-style methods to ground responses in creator material
- A mix of product thinking, early user interviews, and lightweight experimentation to test the idea in practice

### Web apps I built
#### GeekBall
GeekBall is a lightweight prediction game built around football matches. The idea came from wanting a daily game that feels as easy as checking the scores, but still gives people a reason to come back and compete with friends or strangers. Users pick match outcomes before kick-off, earn points for correct predictions, and climb a leaderboard over time. The motivation behind it was simple: I wanted a prediction game that was low-friction, fast to play, and more accessible than traditional fantasy leagues. Developed a client-server architecture utilizing sports APIs to automate the ingestion of live match schedules, team logos, and live scores, supporting real-time user predictions and dynamic leaderboard rankings.
GeekBall: [https://geek-ball.web.app/](#)

#### NorthStand
NorthStand was built to solve a very specific social problem: finding or creating a local place to watch a football match with other fans when you are new to a city or just do not know where people gather. The product is meant to make it easier to discover nearby watch parties and connect with people who share the same team loyalty. The motive behind it was personal and practical — I had experienced the frustration of wanting to watch a game with others but having no clear, simple way to find them.
NorthStand: [https://northstand.me/](#)

#### EatWith
EatWith is a meal-logging and recipe-sharing app designed to make healthy eating feel more practical and less tedious. The idea was to create a space where people could log what they ate, track nutrition over time, and share recipes that they actually wanted to cook again. The motivation behind it was to build something that would be useful in everyday life rather than just impressive in a demo, so the experience had to stay simple and repeatable enough for real use.
EatWith: [https://eatwith-uk.web.app/](#)

#### EatOut
EatOut is a venue-based food app for sharing what you ate out, where you ate it, how much it cost, and whether it was worth it. The point was not to create another generic restaurant review platform, but to capture the small details that are usually missing from recommendation systems: the context of the meal, the price, and the honest take. The motive behind it was to make food recommendations feel more realistic and less abstract by tying them to actual experiences rather than vague opinions.
EatOut: [https://eatout-uk.web.app/](#)

What I used:
- JavaScript for the frontend experience
- Firebase for authentication, database storage, hosting, and rapid deployment
- HTML/CSS for responsive interfaces
- A simple product-first workflow: sketch, build, ship, observe, and improve

### Market Incident Prediction
This project is a market-volatility spike prediction model built around a binary classification task: given the last 30 bars of market behaviour, can the model predict whether a volatility spike will occur in the next 10 bars? The project uses real OHLCV data from Yahoo Finance and focuses on building a sensible forecasting pipeline for noisy financial data.

What I used:
- Python for the full modelling workflow
- yfinance to download SPY market data automatically
- pandas and NumPy for data processing and feature construction
- scikit-learn for preprocessing, evaluation, and metric tracking
- LightGBM for the gradient-boosted tree classifier
- Jupyter-style experimentation and a lightweight script-based workflow for training and inference

## Experience

### Turkish Technology — Turkish Airlines, Digital Solutions
During my internship at Turkish Technology, I worked in the Digital Solutions department on self-service infrastructure for airport operations. The main challenge was to assess whether a camera-based scanning approach could replace more expensive proprietary scanning hardware while still being reliable enough for real passengers in a live environment.

What I used:
- OpenCV for image capture and document processing
- Python for prototyping and evaluation pipelines
- Experimental hardware testing and optics comparison to find a cost-effective setup
- Internal testing workflows to assess accuracy, robustness, and operational feasibility

One of the more interesting parts of the internship was an airport simulation project designed to model passenger flow, queue behaviour, and the impact of different self-service device configurations. The aim was to understand how changes in throughput, waiting times, and staffing assumptions could affect the entire airport experience before making operational decisions.

What I used:
- Python for modelling and data analysis
- SimPy for discrete-event simulation of passenger movement and queueing behaviour
- pandas for processing input data and summarising system behaviour
- Matplotlib for visualising congestion patterns and performance metrics

### ProxoLab
My internship at ProxoLab gave me my first real exposure to a large-scale fintech application with real users, real money, and a production codebase that had already accumulated years of complexity. It was a very different environment from university work because the cost of mistakes was much higher.

What I used:
- The team’s existing full-stack development environment for debugging and feature work
- UI testing and debugging tools to reproduce issues and validate fixes
- Data-structure optimisation and code review practices to improve performance and maintainability
- SQL-backed data flows and general software engineering workflows used in a production setting
