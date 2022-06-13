# WRC_car_dashboard
Interactive dashboard created in Plotly and Dash to visualize the trail and acting forces of the WRC car. 

# The goal 
The goal of this task was to create interactive dashboard, which would be useful tool for rally rider to analysis rider's performance and improve rider's style.

The dashboard would be also great tool for mechanic, it can provide data of the acceleration occurred during rider's training and in case of malfunction detect it's origin (or prevent further damage).

# About data set
Data set has been created based on data collected (meausured) during my friend Tomek's training on the WRC track in Włocławek. The data set contains information about:
- geolocalization of the vehicle,
- accelerations of the vehicle,
- time,
- lap number.

# Run
To run a program:
1) open Jupyter Notebook (or Google Colab),
2) upload data set 'WRC_training.csv',
3) run all of the code-boxes,
4) run latest code-box with app.run_server(), enter the link, and enjoy interactive dashboard 


# Interactive dashboard
With interactive dashboard you can choose laps to analyse Tomek's performance on the Włocławek track. Desired laps you can choose with slider. Visualized data will appear on 4 plots:
- graphs visualizing the movement of the vehicle on the track,
- vehicle speed vs time graph, 
- histogram of vehicle directional accelerations,
- polar diagram of vehicle directional acceleration.

![image](https://user-images.githubusercontent.com/102530541/173320209-ed0ca74f-e2f6-443a-aa12-ac0a94bd7c62.png)


# Technologies:
- Python,
- Pandas,
- Plotly,
- Dash.
