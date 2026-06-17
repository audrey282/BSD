# BSD
How to Use the GUI
Run all the cells above to install libraries, save the model, and create the Flask app files.
Execute the last code cell (the one that starts !python app.py).
Look for the output line that says * ngrok tunnel available at: [your_public_url]. Click on the provided URL.
This will open a new browser tab with your Bike Sharing Demand Predictor GUI.
Enter the required input values (datetime, season, weather, holiday, working day, temperature, humidity, windspeed).
Click 'Predict Demand' to see the model's prediction.
Note: If you restart your Colab runtime, you will need to re-run all the relevant cells (from loading data to model training) before running the GUI cells again, as the model and scaler objects will be lost from memory.
