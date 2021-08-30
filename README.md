# Chart

This is a template to make animation by ipywidgets and plotly.

- First part is used to visualize the map.
- Second part is used to make the chart move.
- Second part-1 ，move center point of chart.
![1](data/1.gif)
- Second part-2 ，move the point on the chart. 
![2](data/2.gif)

---
## Requirements

- ipywidgets==7.6.2
- plotly
- pandas
- numpy

---
## Application

- Ship Movement Simulation
    - **Green** point is the target ship, which can simulate the strategy of  maneuvering to prevent from collision and grounding.
    - **Black** points are the other ships, which are used to simulate the real situation.
    - **Yellow** blocks stand for some obstacles.
    - **Grey** color region is the area near the waypoint.
    - Simulate process: 

![flow_chart_sim_ship](data/sim_ship.png)

![sim_ship](data/ship.gif)
