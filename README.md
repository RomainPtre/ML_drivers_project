# 🚖 Predicting the hottest pickup zones for drivers in Manhattan
This project will allow you to highlight the areas were most Uber pickups occurs depending on the day and hour through the use of a simple function. 

# 🤖 How does it work?
This project is based on the Unsupervised Machine Learning model DBscan. By taking advantage of the density-based clustering model (DBscan) applied on GPS coordinates gathered during April 2014, the model will predict where the most important clusters are located.
It will also isolate noise from relevant informations.

# ⌨ How should you use it?
Just clone or download the whole repository to your drive and open the .ipynb file into your preferred IDE!
You will find details on how functions where created in the notebook.
If you just want result, you can 
  1) Run the show_peak() function on data for some custom informative EDA 📊
![Drivers_EDA](https://github.com/user-attachments/assets/ecd43e30-14cd-460d-b25d-7cb96cd34088)
  2) Run the show_clusters() function on data by specifying the day (in str with capital first letter e.g., 'Friday') and hour (in 24h format) 🗺
![Drivers_DBscan](https://github.com/user-attachments/assets/3e14c76a-a49c-4a84-bcd1-56464264f3e7)

# 🔮 Next steps
I am currently working on another exciting project involving coffee ☕ that should be up on GitHub really soon.
Once this is done, next steps are:
  1) Add some OOP in order to create class and methods that could be called in a python script
  2) Write an app.py to deploy the model throught a streamlit
  3) Add an input section where users could input a day and change DBscan parameters (eps and min_sample) using sliders
