## Car Damage Detection
![](https://i.postimg.cc/05G11hz2/Uploaded.gif)

Well, most of us call our car insurance company, tell them what has happened. And then we wait... for the insurance agent to come and inspect the car,
and take the process forward. This process of inspection take few days.... But we want our car to be back on road ASAP. What can we do to make this process more efficient?

- With the power of deep learning, we can utilize CNN to help us speed up the process of damage detection and transfer learning to train a model that will be able to classify the image of the car, 
  whether the image is the car or not, damage or not and what is the location of the damage.
  
  
### Model Architecture and Pipeline

- **First check**: Check if it's a car or not?  [![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/shejz/car_damage_detection/blob/main/First%20check%20-%20car%20or%20not.ipynb)
- **Second check**: Ensure the submitted image of car is damaged. [![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/shejz/car_damage_detection/blob/main/Second%20check%20-%20prediction.ipynb)
- **Third check**: Check the location of damage in the car. [![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/shejz/car_damage_detection/blob/main/Third%20check%20-%20prediction.ipynb)
- **Fourth check**: Determine the severity of damage. [![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/shejz/car_damage_detection/blob/main/Fourth%20Check%20-%20prediction.ipynb)

**DEMO**: [![Nbviewer](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/shejz/car_damage_detection/blob/main/Integration%20-%20Combining%20all%20checks.ipynb)





