## Workout Predictor and Planner

# Goal
Build a regression model that can moderately accurately suggest future workout reps/weight based on predictive analysis.

# Scope
Make a functional regression model to perform predictions, as well as a basic frontend that can send data to my SQL db

# Future Plans
* Find a large dataset for workouts
* Train a neural network to predict future progress
* Add the ability to import data from other workout sites


# Tech Stack
- Languages:
  1. JavaScript(React)
  2. Python(Flask)
  3. SQL(PostgreSQL)
- Libraries/tools:
  1. React
  2. Flask
  3. Pandas
  4. Scikit-learn
  5. Matplotlib
  6. PostgreSQL
  7. Git/ Github
  8. Vercel
  9. Supabase
- Storage - Supabase DB storing exercises with dates, sets, weights, and reps.
- Data Source - My local Strong (workout planner I currently use) history, manually exported as a CSV and read with Pandas

# Milestone List
1. Make a non-interactive frontend
2. Establish SQL schema, and tables
3. Establish frontend writes to the tables, as well as input validation
4. Export and Parse Strong CSV data
5. Add Strong CSV data to the SQL table, backfilling progress
6. Prepare data for modeling and make the prediction input/output
7. Train a regression model and evaluate it's predictions against my daily workouts
8. Connect the model to flask and display suggested weight/reps on the frontend
9. Deploy to Vercel
10. Finish documentation and create demo
