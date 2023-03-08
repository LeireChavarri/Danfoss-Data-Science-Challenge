# Danfoss Data Science Challenge - IT Days 2023

## Help us reduce the energy consumption of buildings!
![image](https://user-images.githubusercontent.com/63345770/222718762-f48361fd-9189-41b1-826d-e83a83edee10.png)

**Electronic controllers (ECL)** are intelligent temperature regulators for district heating and domestic hot water systems. By means of weather compensation, they can be adapted to a variety of district heating systems, ensuring a high level of comfort and optimum energy utilization. 
The weather compensation curve (Heat Curve) assures that the temperature of the water flowing thought the radiators system is high enough to ensure indoor comfort levels even on very cold days.


![image](https://user-images.githubusercontent.com/63345770/222718952-3f37ba2f-b4aa-4f07-bc28-1b1a6c8f49b2.png)



*This is an example of the weather compensation curve (Heat Curve):*

|Outdoor temperature [°C] | Supply temperature [°C]  |   
| :---:   | :---: |
| -30 | 95   | 
| -15 | 90   | 
| -5 | 80   | 
| 0 | 70   | 
| 5 | 60   | 
| 15 | 35   | 


Traditionally, the Heat Curve for space heating is set based on buildings construction year and through trial and error methods where often it is overestimated to avoid underheating of apartments. Consequently, consuming more energy than expected.
Now, with the use of data we capture from the building sensors and the ECL controllers, we can set the optimal Heat Curve to assure highest energy savings and comfort! But for this, we need your help. 

Find [here](challenge_data.csv) a link to our dataset where you will find the data consisting of Outdoor Temperature, Indoor Temperature, Heating Curve (all in Celsius) and datetime for a specific building.

**We want you to find what is the most optimal Heat Curve for heating the building to 21°C for the following points:**
	
|Outdoor temperature [C] | Supply temperature [C]  |   
| :---:   | :---: |
| -10 | x   | 
| -5 | x  | 
| 0 | x   | 
| 5 | x  | 
| 15 | x   | 



Please send us your problem resolution to xxxxxx@danfoss.com and tell us:
- how you solved it and what methods you have applied. Visualizations are a plus!
- What other data driven techniques can be implemented to reduce the consumption of the building further?







